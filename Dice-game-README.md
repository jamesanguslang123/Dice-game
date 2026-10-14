# Python Dice Game 🎲

## About the Project

This is a two-player dice game written in Python. Players take turns rolling a virtual six-sided dice and try to earn as many points as possible.

Rolling an even number earns the player one point, while rolling an odd number resets their score to zero and ends their turn. After both players have finished, the game compares their scores to determine the winner. Players can also choose to play multiple rounds.

## Features

- Random dice rolls using Python's `random` module.
- Two-player turn-based gameplay.
- Even and odd number detection using the modulo operator (`%`).
- A scoring system to track each player's points.
- The option to roll again or end the game.
- The ability to play again after a round finishes.

## What I Learned

While developing this project, I practised using:

- Variables to store and update scores.
- `while` loops to control gameplay.
- `if`, `elif` and `else` statements to determine outcomes.
- The `random` module to generate dice rolls.
- User input to control the game.
- Debugging and testing to fix problems with the replay system.

## Challenges and Improvements

One issue I encountered was that the game did not correctly respond when a player was asked whether they wanted to play again. I learnt the difference between `=` (assignment) and `==` (comparison) and corrected the code so that the player's response updates the replay variable.

I also used `.lower()` to make the input handling more consistent when players enter answers such as `Yes` or `YES`.

## How to Run

1. Install Python 3.
2. Download the Python file from this repository.
3. Open a terminal in the folder containing the file.
4. Run:

   `python Python-Dice-game.py`

## Future Improvements

- Add a target score that determines the winner.
- Validate user input and handle unexpected answers.
- Improve the interface and display the scores more clearly.
- Add more game modes.
