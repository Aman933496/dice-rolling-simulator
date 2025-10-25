🎲 Dice Rolling Simulator

A simple Python program that simulates rolling a dice and displays the result. This project is great for beginners to understand how loops, functions, and random number generation work in Python.

🚀 Features

Simulates the rolling of a standard 6-sided dice

Generates random values between 1 and 6

User-friendly and interactive console interface

Option to roll the dice multiple times

📁 Project Structure

Dice-Rolling-Simulator/ 

│

├── dice_simulator.py   # Main program file

├── README.md           # Documentation file

🧠 Code Explanation
| Line / Part                         | Explanation                                                                   |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| `import random`                     | Imports Python's built-in random module to generate random numbers.           |
| `def roll_dice():`                  | Defines a function that simulates rolling a die.                              |
| `return random.randint(1, 6)`       | Generates and returns a random number between 1 and 6, like a real dice roll. |
| `def main():`                       | Main function where the program starts running.                               |
| `print("🎲 Welcome...")`            | Displays a welcome message.                                                   |
| `while True:`                       | Starts an infinite loop so the user can roll the dice multiple times.         |
| `input("Press Enter...")`           | Waits for the user to press Enter to roll the dice.                           |
| `result = roll_dice()`              | Calls the function and stores the rolled number.                              |
| `print(f"You rolled: {result}")`    | Displays the number rolled.                                                   |
| `choice = input(...).lower()`       | Asks if the user wants to roll again and converts input to lowercase.         |
| `if choice != "y": break`           | Exits the loop if the user types anything other than “y”.                     |
| `if __name__ == "__main__": main()` | Ensures the program runs only when directly executed, not when imported.      |

