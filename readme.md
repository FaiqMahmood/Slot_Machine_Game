# Slot Machine Game

This is a simple Python console-based slot machine game. Players can deposit money, choose the number of lines to bet on, and place bets on each line. The game then simulates a slot machine spin with randomly generated symbols in a grid. The player can win based on matching symbols on the selected lines.

## Game Rules

**Symbols**: The slot machine consists of symbols labeled as "A," "B," "C," and "D," each with a specific count and value.

`symbol_count = { "A": 2, "B": 4, "C": 6, "D": 8 }`

`symbol_value = { "A": 5, "B": 4, "C": 3, "D": 2 }`

**Lines**: Players can choose the number of lines to bet on, with a maximum of 3 lines.

`MAX_LINES = 3`

**Betting**: Players can place bets on each line, with a minimum bet of $1 and a maximum bet of $100.

`MIN_BET = 1`

`MAX_BET = 100`

## Game Functions

- `check_winnings(columns, lines, bet, values)`: Checks for winning combinations in the slot machine spin.

- `get_slot_machine_spin(rows, cols, symbols)`: Generates a random slot machine spin grid.

- `print_slot_machine(columns)`: Prints the slot machine grid.

- `deposit()`: Allows the player to deposit money to start the game.

- `get_num_of_lines()`: Prompts the player to enter the number of lines to bet on.

- `get_bet()`: Prompts the player to enter the bet amount for each line.

- `spin(balance)`: Simulates a spin, checks for winnings, and updates the player's balance.

- `main()`: The main game loop where the player can deposit money, play spins, and quit the game.

## How to Play

1. Run the script.
2. Deposit money when prompted.
3. Press Enter to play a spin or 'q' to quit.
4. Choose the number of lines and bet amount.
5. View the slot machine spin result.
6. Check if you won and see the winnings.
7. Repeat until you decide to quit.

**Enjoy the game!**
