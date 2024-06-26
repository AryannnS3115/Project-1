# Rock,Paper & Scissor game 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
This is a simple game developed in python.
Python is a multipurpose language and one can do anything with it. Python can also be used for game development. Let’s create a simple command-line Rock-Paper-Scissor game without using any external game libraries like PyGame. In this game, the user gets the first chance to pick the option between Rock, paper, and scissors. After the computer select from the remaining two choices(randomly), the winner is decided as per the rules.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Code Explanation:

The code starts by printing a message that states the rules of the game.
The first line in the code prints “Rock vs paper->paper wins.”
This is because if you have a rock, and you play against someone who has a piece of paper, the rock will beat the paper.
The next line in the code prints “Rock vs scissor->Rock wins.”
This is because if you have a rock, and you play against someone who has a scissors, the rock will beat the scissors.
The last line in the code prints “paper vs scissor->scissor wins.”
This is because if you have a piece of paper, and you play against someone who has a scissors, then the piece of paper will beat the scissors.
The code will print the following output: Winning Rules of the Rock paper scissor game as follows: Rock vs paper->paper wins Rock vs scissor->Rock wins paper vs scissor->scissor wins
The code starts by asking the user for a choice.
The code then checks to see if the input is 1, 2, or 3.
If it is not one of those values, the code sets the choice_name variable to ‘Rock’ if choice == 1, ‘paper’ if choice == 2, and ‘scissor’ if choice == 3.
The next part of the code asks the user for their computer turn.
The code uses a random number generator to choose between 1, 2, and 3.
This value is stored in comp_choice_name.
Next, the code loops until comp_choice equals choice.
In each loop iteration, comp_choice will be randomly chosen from 1-3 and stored in comp_choice_name.
Once comp_choice equals choice, this means that the computer has chosen rock as its turn!
Finally, it prints out both choices so that everyone can see what happened (user choice is: Rock V/s paper; Computer choice is: Rock V/s scissor).
The code will ask the user for a choice between rock, paper and scissors.
Once the user enters their choice, the code will randomly choose one of those options as the computer’s turn.
The code then prints out the chosen option and the user’s choice.
Finally, it loops back to ask for another choice from the user.
===================================================================================================================================================================
Number guessing game in Python 
Algorithm: 
=>Below are the Steps:
=>User inputs the lower bound and upper bound of the range.
=>The compiler generates a random integer between the range and store it in a variable for future references.
=>For repetitive guessing, a while loop will be initialized.
=>If the user guessed a number which is greater than a randomly selected number, the user gets an output “Try Again! You guessed too high“
=>Else If the user guessed a number which is smaller than a randomly selected number, the user gets an output “Try Again! You guessed too small”
=>And if the user guessed in a minimum number of guesses, the user gets a “Congratulations! ” Output.
=>Else if the user didn’t guess the integer in the minimum number of guesses, he/she will get “Better Luck Next Time!” output.
