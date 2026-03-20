I started working on my project by importing the libaries I needed to run the application, to start with this i followed 
lecture 7's random function as i needed the cards chosen in my application to be random. I expanded on this by using the 
shuffle command from the random libary to randomise the deck order then the sample command to get unique cards each time. 
I tried to implement this in a custom libary (cards.py) but was unable to get to interact with the main file in the way i 
wanted so i moved the code over. 
I implelented OOP with the use of the name class in orderr get the players name and display it in the menu, I used lecture 9 
for the general form on how to use this then adapted it for use in my appliocation. 
I broke down the game into several functions and used some multiple times (hand value functions) in order to minimise the amount of suplicated lines in the application. 
I struggled getting these functions to work for a while as i needed to get the total to adjust for any aces to prevent the user from going bust (total over 21),
I was trying to search the hand for the ranks and if it saw a ace it would add to the aces total. 
However, when searching this way it would find no results as the string were saved in rank, i figured this out by printing out the rank in hand 
then based how many aces there were on the rank.   
I added and removed cards from the hands by pulling a random sample from the deck then appending it to the list,  
this ensured that all cards were unique and that there were no duplicates to make the game seeem as if it were using one deck. 
I finished the application by implementing a file I/O to track the players wins and losses, I followed lecture 8's explanation on this in order to implment it. 
I open the file using "a" to append the results of the game to results.txt then flush to ensure the string is added. 
Then I read it using "r" and print out the result to show to the player.
