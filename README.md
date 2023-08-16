# WarCardGame
Welcome to the thrilling world of the War Card Game! Engage in an epic battle of cards against the computer and experience the excitement of each drawn card. Will you emerge victorious, or will the computer conquer the realm of cards? Enter the arena and let the games begin!

## Table of Contents
- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)

## About
The War Card Game is a simple two-player card game implemented in Python. In this game, you and the computer will battle each other using a standard deck of playing cards. The game continues until one of the players runs out of cards, and the player with cards remaining is declared the winner.

## Features
- **Dynamic Gameplay:** The game employs a dynamic gameplay loop, allowing you to play against the computer round by round. You can choose to continue or stop after each round, adding an interactive element to the game.
- **Deck Manipulation:** The Deck class provides essential methods for building, shuffling, drawing, and adding cards to decks. The Card class, in turn, facilitates the display of card values and suits, including special cards.
- **"War" Mechanism:** In case of tied card values, the game enters a "war" scenario. The start_war method in the WarCardGame class simulates this event by drawing additional cards to break the tie and determine the round winner.

## Getting Started
Get ready for an exciting gaming experience! Follow these steps to set up and run the game project on your computer.

### Prerequisites
- Python 3 or superior installed on your system.
- Terminal.

### Installation and configuration 
1. Download the project code from its source. You can do this by either downloading the code directly from [the source](https://github.com/catarinarodriguesv/WarCardGame.git) or by cloning the repository using a version control tool like Git.
2. Open a terminal and navigate to the directory where you've downloaded or cloned the project.
3. Run the game by using the following command: **python main.py**

### Play the game:
- Press enter to draw a card.
- The game will show the results of the round.
- The game will determine the round winner and update the counters.
- Rounds continue until either you or the computer's counter reaches 0.


### Exiting the game:
At the end of each round, you are asked if you want to play another round (**Enter**) or if you want to exit (**X**). But to exit the game at any time, you can press **Ctrl + C** in the terminal.

Congratulations! You've successfully set up and run the war card game project locally on your computer. Enjoy playing against the computer and exploring the world of programming concepts through this interactive game.
