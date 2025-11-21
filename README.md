# ♟️ Chess Game Python Project

This Python project presents a part of a chess game simulation.
The goal of the program is to determine which black pieces a single white piece can capture from a user-defined board state, using standard chess movement rules.

**Google Colab:** [Project in Google Colab environment](https://colab.research.google.com/drive/141w3ZMPIO_Lnkd9EywHYlly4K0By2B7r?usp=sharing)

**Jupyter Notebook file:** [Project saved as .ipynb in this repo](jupyter_notebook/Chess_project.ipynb)

**🐍 Python library:** `tabulate`

## 🎯 Core Functionality

The program must execute a three-step process:

* **White Piece Input:** program prompts the user to specify only one white figure and its position (e.g., bishop c2).
* **Black Pieces Input:** program allows the user to input between 1 and 16 black figures and their positions (e.g., pawn d5), stopping when the user enters "done" or when 16 black figures have been added to the board. 
* **Determine Captures:** Based on standard chess movement rules, the program returns a list of all black pieces and their positions that are currently capturable by the single white piece. If no capturable pieces available, the program returns a message clearly stating that no captures are possible.

## 🔒 Key Requirements & Validation

The program must rigorously validate all user inputs:

* **Format:** all position inputs must be valid chess coordinates (a-h, 1-8, e.g., a1).
* **Figure Names:** must confirm that the piece name is valid (e.g., pawn, rook, bishop, etc.).
* **White Piece Limit:** only one white figure is allowed.
* **Black Piece Limit:** must accept a minimum of one and a maximum of sixteen black figures.
* **"Done" Command:** the user can only enter "done" to stop adding pieces after at least one black piece has been successfully added to the board.
* **Final Output:** the program must display either a list of all capturable black pieces and their positions, or a message clearly stating that no captures are possible.
