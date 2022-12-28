# Poker Game

A single player 5 cards poker game.

## Description

This application is built using python and one can play a poker game of 5 cards which will give a score based on the types of cards you get.
Intially, the player will have 5 cards with them, after that it will give an option to either hold those cards or replace them.
To replace the cards just type which card numbers you want to replace in the terminal
Each round cost is 5 points which will be taken out of the total points
Initially, the player will have 100 points to start with.

| Type of Cards  | Second Header |
| -------------- | ------------- |
| Royal Flush    | 2000 Points   |
| Straight Flush | 250 Points    |
| Four of a Kind | 125 points    |
| Full House     | 40 Points     |
| Flush          | 25 Points     |
| Straight       | 20 Points     |
| Three of a Kind| 15 Points     |
| Two Pairs      | 10 Points     | 
| Jacks or Better| 5  Points     |


If there are no such cards the application will say "You had bad cards, no points for these cards." and the player will have no points for that round.

I have added base cases for the game, if the player reaches 0 points, they cannot continue to play the game, also if the player reaches 2500 points which is the maximum points, the game terminates.

The application will terminate if the player types "exit" in the console.

NOTE: I have used random.shuffle() for shuflling the cards, so it gets difficult to get the exact match of cards each time. 
      To make sure that my application is working and I have all the conditions matching I have created a test() function which will check all of my conditions.
      I have not called that function while submitting. I will demonstarted it live to the TA during my presentation. 

Extra: It was told in the lectures that the professor is not expecting to create a poker game and rather a simple game of our own. 
       I took the challenge and created a poker game itself.

## Getting Started
To run the application just type in the terminal ```python main.py```

## Author
Preet Dabhi (10459151)
