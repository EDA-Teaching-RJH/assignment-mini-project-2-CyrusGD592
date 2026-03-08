import random
from itertools import product 
from random import shuffle 

Suits = ["Clubs ", "Hearts ", "Spades ", "Diamonds "] 
Ranks = ['Ace ', '2 ', '3 ', '4 ', '5 ', '6 ', '7 ', '8 ', '9 ', '10 ', 'Jack ', 'Queen ', 'King '] 

deck = list(product(Ranks, Suits)) #creates deck 
shuffle(deck)  
hand = random.sample(deck,k=2) # sets hand to 2 unique cards

##for i in range(0, len(deck), 4): 
   # print("{} {} {} {}".format(
        #deck[i][0] + deck[i][1],
        #deck[i+1][0] + deck[i+1][1],
        #deck[i+2][0] + deck[i+2][1],
        #deck[i+3][0] + deck[i+3][1]
   # ))  #test to see deck


def card_value():
 total = 0
 value = {'Ace ' :11 , '2 ' :2, '3 ' :3, '4 ' :4, '5 ':5, '6 ':6, '7 ':7, '8 ':8, '9 ':9, '10 ':10, 'Jack ':10, 'Queen ':10, 'King ':10} 
 print(hand) 
 for i in hand: 
  total += value.get(i[0], 0) 
 print(f"Hand value:  {total}") 



card_value()