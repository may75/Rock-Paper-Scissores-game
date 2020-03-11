# Rock-Paper-Scissores-game

In this project I have made the Rock paper scissor game. I compiled it in Spyder – Python 3.7 It is a very popular and
easily memorized rule determines the winner: “Rock breaks scissors, scissors cuts paper, paper covers rock.
” It contains one class and two method and Inside the while loop and if statement to make flexible choice to the user 
and then for or generating the choice of the computer by used the random function through inherent from computer class. 
if statement for comparing the two choices. Depending upon the rules the winner is selected.

This the program menu and user have to enter his choice.. 

************** Welcome to my Rock-Paper-Scissors Games **********
*                           OPTIONS                             *
* [1] - Start new game                                          *
* [2] - Load the game                                           *
* [3] - Exit                                                    *
*****************************************************************


•	Game rules:
          ** The user play against the computer
          ** The first one who scores 3 points WINS the game!
          ** If you want to save your game, just type 'save'.
          ** If you forgot the rules, just type 'help'.
          ** If you want to quit the game  and go to main menu just type 'quit'.
          ** If the user want to load the pervious game can choose " option 2 from the main menu
          ** If user want to exit the program can choose option 3 from the main menu.
### Classes
At this program there one class (Computer), which representation of the randomly choice for the computer. Which select between rock, paper and scissors.
### Methods
There is two method at this program:
•	Def welcome()
The main menu of the game which let the user to select one of three option, first one is start new game, second one load the game and third one exits the game by using while and if function.

•	Def letplay(option)
The letsplay method is execute the main menu of the program, in option one (new start) let user enter his/her choices and let the computer generating the choice by the random function that execute from computer class, then compare it together to have result by using list, tuples and dictionary to have winner and lost. In option two (load the game) using try and except to retrieve the last score saved in text file , and finally option three (exit) to exit the program. 

