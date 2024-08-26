# slot-machine-game

This is a simple console-based slot machine game implemented in Python. Players can deposit money, place bets, spin the slot machine, and potentially win based on the results of the spin.

## Features

- **Deposit**: Players start by depositing an initial amount of money to play with.
- **Betting**: Players can choose the number of lines to bet on and the amount they wish to bet per line.
- **Slot Machine Spin**: The slot machine generates random symbols across rows and columns to determine winnings.
- **Winning Calculation**: The game calculates winnings based on matching symbols across the chosen lines.
- **User Interface**: The game is text-based, with inputs and outputs displayed in the console.

## Game Rules

1. **Deposit Money**: Before starting, you need to deposit money into your balance.
2. **Choose Number of Lines**: You can choose to bet on 1 to 3 lines. More lines increase the chances of winning but also increase the total bet amount.
3. **Place a Bet**: Enter the amount you want to bet per line. The total bet is calculated as the bet amount multiplied by the number of lines.
4. **Spin the Slot Machine**: After placing a bet, the slot machine spins and displays a random set of symbols.
5. **Determine Winnings**: If you have matching symbols on the lines you bet on, you win a corresponding amount based on the symbol values and the bet placed.
6. **Repeat or Quit**: You can continue playing with your remaining balance or quit the game.

## Symbol Details

The slot machine uses four different symbols with varying frequencies and values:

- **Symbol "A"**: Appears 2 times and has a value multiplier of 2.
- **Symbol "B"**: Appears 4 times and has a value multiplier of 4.
- **Symbol "C"**: Appears 6 times and has a value multiplier of 3.
- **Symbol "D"**: Appears 8 times and has a value multiplier of 2.

## How to Run the Game

1. **Install Python**: Ensure you have Python installed on your system (Python 3.x recommended).
2. **Download the Script**: Save the provided Python code into a file, e.g., `slot_machine.py`.
3. **Run the Script**: Open your terminal or command prompt, navigate to the directory containing `slot_machine.py`, and run the game using the command:

   ```bash
   python slot_machine.py
