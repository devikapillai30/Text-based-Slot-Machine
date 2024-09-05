# Slot Machine Game

This is a simple text-based slot machine game implemented in Python. The game allows users to deposit money, place bets on multiple lines, and spin the slot machine to win based on matching symbols. The winnings are calculated based on the symbols and their respective values.

## Table of Contents
- [How to Play](#how-to-play)
- [Features](#features)
- [Game Rules](#game-rules)
- [Code Overview](#code-overview)
- [Contributing](#contributing)

## How to Play
1. **Deposit Money**: Start by depositing an amount of money you want to play with.
2. **Place Bets**: Choose the number of lines (1-3) to bet on. Then, place a bet amount for each line. The total bet is calculated as the bet amount multiplied by the number of lines.
3. **Spin the Machine**: Press Enter to spin the slot machine and see the outcome.
4. **Check Winnings**: If you win, your winnings will be added to your balance. If not, the bet amount is deducted from your balance.
5. **Quit the Game**: You can quit the game anytime by entering 'q'.

## Features
- **Multiple Lines Betting**: Bet on up to 3 lines to increase your chances of winning.
- **Random Spins**: Each spin generates a random set of symbols.
- **Dynamic Winnings Calculation**: Winnings are calculated based on the symbols and their respective values.
- **Interactive User Input**: Easy-to-follow prompts guide the user through the game.

## Game Rules
- The slot machine has 3 rows and 3 columns.
- Symbols have different values and occurrences:
    - "A": Occurs 2 times, value 5.
    - "B": Occurs 4 times, value 4.
    - "C": Occurs 6 times, value 3.
    - "D": Occurs 8 times, value 2.
- A win is achieved if the same symbol appears across the selected lines.
- Winnings are calculated by multiplying the symbol's value by the bet amount per line.

## Code Overview
The main components of the code include:
- **deposit()**: Prompts the user to deposit an amount of money.
- **get_number_of_lines()**: Asks the user to choose the number of lines to bet on.
- **get_bet()**: Prompts the user to place a bet on each line.
- **get_slot_machine_spin()**: Generates random symbols for
