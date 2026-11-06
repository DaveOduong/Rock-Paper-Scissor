# Rock Paper Scissors Game (Python)

## Description
A simple Python Rock Paper Scissors game where the player competes against the computer. The computer randomly selects rock, paper, or scissors, and the program determines the winner based on the rules of the game.

## Features
- Allows the player to choose Rock, Paper, or Scissors.
- Computer randomly selects its choice.
- Displays both the player's and computer's choices.
- Determines whether the player wins, loses, or ties.
- Uses a separate function to check winning conditions.

## How It Works

### 1. Play Function – `play()`
- Requests the player's choice.
- Generates a random computer choice using `random.choice()`.
- Compares both choices.
- Returns the game result.

### 2. Winning Function – `is_win(player, opponent)`
Checks the winning combinations:

- Rock beats Scissors.
- Scissors beats Paper.
- Paper beats Rock.

Returns `True` when the player wins.

## Technologies Used
- Python
- Random Module
- Functions
- Conditional Statements (`if`)
- User Input (`input()`)
- Return Statements

## How to Run
1. Install Python.
2. Save the code as `rock_paper_scissors.py`.
3. Open a terminal in the project folder.
4. Run:

```bash
python rock_paper_scissors.py
```

## Example Output

```text
What's your choice? (r) for rock (p) for paper (s) for scissors
r
You have picked r and The Computer picked s
You won
```

## Learning Objectives
This project demonstrates how to use Python functions, random selection, conditional logic, Boolean return values, and user input to create a simple interactive game.

## Game Rules
- Rock (`r`) beats Scissors (`s`).
- Scissors (`s`) beats Paper (`p`).
- Paper (`p`) beats Rock (`r`).
- Matching choices result in a tie.
