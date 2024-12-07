# Game Domination

This is a Python-based game of "Domination" with a graphical user interface (GUI). 

**Game Rules:**

* **Objective:** To score more points than the computer opponent.
* **Gameplay:**
    * The game is played on a grid.
    * **The player always plays with the marker 'X'.** 
    * The computer opponent plays with 'O'.
    * Players take turns placing their markers on the grid.
    * Points are awarded for the following:
        * **Square (6 points):** Forming a perfect square with your markers.
        * **L-shape (3 cells) (7 points):** Forming an 'L' shape with your markers.
        * **Diagonal (3 cells) (7 points):** Forming a diagonal line with your markers.
        * **Full Row/Column (10 points):** Completing an entire row or column with your markers.
        * **3 Consecutive Cells (5 points):** Place three markers consecutively in a row or column.
* **AI Opponent:**
    * The computer opponent utilizes an AI algorithm to:
        * Maximize its own score.
        * Minimize your potential score.

**Project Structure:**

* `grid_domination.py`: Contains the core game logic, including:
    * Game board representation.
    * Player and AI move handling.
    * Scoring calculations.
    * Game state management.
* `grid_domination_gui.py`: Implements the graphical user interface using a library like:
    * Tkinter (for a simpler, cross-platform GUI)
