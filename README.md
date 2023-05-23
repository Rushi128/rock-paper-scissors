

# Rock-Paper-Scissors Game with OpenCV

This is a simple implementation of the classic rock-paper-scissors game using Python and OpenCV. The game allows you to play against the computer by making hand gestures for rock, paper, or scissors.

## Game Rules

1. The game starts when the webcam feed is displayed.
2. Position your hand in front of the camera, making one of the following gestures:
    - Fist: Represents "Rock"
    - Open hand: Represents "Paper"
    - Two fingers extended: Represents "Scissors"
3. The computer randomly selects its gesture.
4. The game determines the winner based on the following rules:
    - Rock beats Scissors
    - Paper beats Rock
    - Scissors beats Paper
    - If both the player and computer make the same gesture, it's a tie.
5. The result (win, lose, or tie) is displayed on the screen.
6. Press the 'Q' key to quit the game.

## Prerequisites

- Python 3.x
- OpenCV library
- Webcam or camera device

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/rock-paper-scissors.git
```

2. Install the required dependencies:

```
pip install opencv-python
```

## Usage

1. Open a terminal and navigate to the project directory.
2. Run the game script:

```
python game.py
```

3. Allow access to the webcam when prompted.
4. Position your hand in front of the camera to make your gesture.
5. View the result displayed on the screen.
6. Press 'Q' to quit the game.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for more information.

