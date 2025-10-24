# ♟️ Python Chess Engine

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A high-performance, bitboard-based chess engine written in Python, complete with a playable GUI built using Pygame. This project was developed as a deep dive into the worlds of chess programming and artificial intelligence.

It supports all standard chess rules and is designed for experimentation, learning, and as a foundation for more complex chess AI projects.

![Gameplay Screenshot 1](https://i.imgur.com/CvAvgbh.png)
![Gameplay Screenshot 2](https://i.imgur.com/72xG6ZI.png)



## ✨ Features

* **Efficient Bitboard Representation**: Utilizes bitboards for fast and efficient move generation and board evaluation.
* **Complete Rule Set**: Full implementation of all chess rules, including:
    * Pawn promotions
    * En passant captures
    * Castling (king-side and queen-side)
    * Stalemate and checkmate detection
* **Playable GUI**: A clean and simple graphical interface powered by Pygame, allowing you to play against the AI or another human.
* **AI Opponent**: A built-in AI that uses a classic search algorithm to find the best move.
* **Move Validation**: Highlights legal moves for a selected piece, making it user-friendly.

## 🧠 The AI Engine

The brain of this engine is a **Minimax search algorithm with Alpha-Beta Pruning**. This allows the AI to search several moves deep into the game tree, pruning branches that are guaranteed to be worse than a move already found. This significantly speeds up the decision-making process without sacrificing the quality of the move.

The board's position is evaluated using a heuristic function that considers:

* **Material Advantage**: The total value of pieces for each side.
* **Piece-Square Tables**: The strategic value of a piece's position on the board (e.g., a knight in the center is more valuable than one in a corner).
* **King Safety**: Basic checks to evaluate the safety of the king.

This is a great foundation for anyone interested in game theory and AI search algorithms.

## 🛠️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

* Python 3.9 or higher
* Git

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/K6EDWIN/Chess.git

    ```
3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
    *(Note: Your `requirements.txt` should contain `pygame`)*

## 🚀 Usage

To run the game, execute the Gui script from the root directory:

```sh
python gui.py
