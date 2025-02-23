# Rock-Paper-Scissors Game

## Overview
This is a simple Rock-Paper-Scissors game implemented in Python. The game allows a player to compete against the computer by selecting one of the three options: Rock, Paper, or Scissors. The winner is determined based on the classic rules of the game.

## How It Works
1. The player selects Rock, Paper, or Scissors by entering a corresponding number:
   - `0` for Rock
   - `1` for Paper
   - `2` for Scissors
2. The computer randomly selects one of the three options.
3. Both choices are displayed using ASCII art.
4. The winner is determined based on the following rules:
   - Rock beats Scissors.
   - Scissors beats Paper.
   - Paper beats Rock.
   - If both choices are the same, it's a tie.

## Prerequisites
- Python 3.x must be installed on your system.

## Installation and Running the Game
1. Clone this repository or copy the script to your local machine.
2. Open a terminal or command prompt.
3. Run the script using Python:
   ```bash
   python rock_paper_scissors.py
   ```
4. Follow the on-screen instructions to play.

## Code Explanation
- The script defines three ASCII representations for Rock, Paper, and Scissors.
- The player inputs their choice as an integer (0, 1, or 2).
- The computer randomly selects a choice.
- Both choices are displayed, and the winner is determined using `if-elif` conditions.

## Example Gameplay
```
What do you choose? Type 0 for Rock, 1 for Paper, or 2 for Scissors?
1
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)

Computer chose:
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)

You win.
```

## Future Enhancements
- Add a graphical user interface (GUI) using Tkinter or Pygame.
- Allow multiple rounds with score tracking.
- Enhance the user experience with sound effects and animations.

## License
This project is open-source and free to use under the MIT License.

## Author
- Developed by Sameeha Firdaus.

