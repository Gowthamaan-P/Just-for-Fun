<div style="text-align: justify;">

# Point Connect

## Overview

Point Connect is a Python game based on the Sylvester–Gallai theorem. The objective of the game is to connect $2n$ points on a plane using $n$ lines with the constraint that no two lines should intersect. The game provides an engaging challenge that requires spatial awareness and strategic thinking.

## Sylvester–Gallai theorem

The Sylvester–Gallai theorem in geometry states that every finite set of points in the Euclidean plane has a line that passes through exactly two of the points or a line that passes through all of them. It is named after James Joseph Sylvester, who posed it as a problem in 1893, and Tibor Gallai, who published one of the first proofs of this theorem in 1944. A line that contains exactly two of a set of points is known as an ordinary line. Another way of stating the theorem is that every finite set of points that is not collinear has an ordinary line.

For more details, visit the [Wikipedia](https://en.wikipedia.org/wiki/Sylvester%E2%80%93Gallai_theorem) page.

## Features

- **Point Generation**: Automatically generates $2n$ non-collinear points on a plane.
- **Line Drawing**: Allows the player to connect points using lines.
- **Game Logic**: Connect two points at a time. Connect points such that no two lines intersect
- **User Interface**: Simple and intuitive interface for an enjoyable gaming experience.

## How to Play

1. **Run the Game**: Execute the Python script `main.py`.
2. **Point Generation**: The game will ask for the number of points $n$ and automatically generate $2n$ non-collinear points on the screen where, n points will be red and n points will be in blue
3. **Connect Points**: Use your mouse to draw click on the points, you want to connect. Only a red and blue pair can be joined. Remember the points you have clicked. The game tests your recalling ability and doesnot allow a redo selection
4. **Winning Condition**: Successfully connect all points without any intersecting lines.

## Requirements

- Python 3.8 or above
- Pygame library

## Usage

1. Clone the project:

   Use [DownGit](https://downgit.github.io/#/home) to download the project. Use the following URL:

   ```
   https://github.com/Gowthamaan-P/Just-for-Fun/tree/main/Points%20Connect
   ```

2. All the above packages are listed in the `requirements.txt` file. To install them, simply execute the following command:

   ```sh
   $ pip install -r requirements.txt
   ```

   By installing the listed packages, you can ensure that all necessary dependencies are met for running the project smoothly.

3. Run the game:

   ```sh
   python main.py
   ```

## Further Development

The game is just a simple experiment. Many enhancements can be made to improve the user experience and the overall quality of the game.

- **Draw Lines**: Enable drawing lines instead of clicking on the points.
- **Scoring System**: Implement a scoring system to track the player's performance based on the number of lines used or the time taken to complete the game.
- **Levels of Difficulty**: Add levels with increasing complexity, such as more points or additional constraints on line placement.
- **Visual Enhancements**: Improve the visual aesthetics of the game with better graphics and animations.
- **Undo Functionality**: Allow players to undo their previous line placements, providing more flexibility in gameplay.
- **Multiplayer Mode**: Introduce a multiplayer mode where players can compete against each other or collaborate to solve challenges together.
- **Algorithm Improvement**: Improve the algorithm to generate the non-collinear points.

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE.md) file for details.

</div>
