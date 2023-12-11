# Blackjack Game

## Authors
Dyson Lewis, Matthew Godinez, Pedro Sandoval

## Date Published
December 10th, 2023

## Project Description
This project implements a simple console-based Blackjack game using C++. The game follows standard Blackjack rules and includes features such as betting, splitting, and doubling down. The program is structured with classes to represent the game entities, and it utilizes concepts from discrete structures to determine optimal player moves.

## Programming Approaches
- Object-Oriented Design: The program is structured using classes to represent key entities such as the game, player, deck, and probability calculations. This promotes code organization and modularity.
- Discrete Structures: The PlayerActionInfo class incorporates arrays to store information about optimal actions for different hand values, incorporating concepts from discrete structures to guide player decisions.
- Randomization: The Deck class utilizes randomization to shuffle cards, providing an element of unpredictability in the game.

## How to Use the Program
1. Compile the program using a C++ compiler (e.g., g++), or an IDE, I used NetBeans.
2. Run the executable file generated.
3. Follow on-screen prompts to:
    - Place bets: Enter the desired bet amount when prompted.
    - Choose actions during your turn: Enter the corresponding number for the action (e.g., 1 for Hit, 2 for Double, 3 for Stand).
    - Decide on split actions if applicable.

## Additional Notes
- The game loop allows for multiple rounds until the player decides to stop.
- Make sure to follow the on-screen instructions for input during the game.
