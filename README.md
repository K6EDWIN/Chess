<div align="center">

# ♟️ Python Chess Engine

A high-performance, **bitboard-based chess engine** written in Python.  
Supports full chess rules including castling, en passant, promotions, and advanced move generation.  
Designed for experimentation, learning, and integration with chess AI projects.  

</div>

---

<div align="center">

## 🎯 Features

- **Complete Chess Rules**:
  - Castling (Kingside and Queenside)  
  - En passant captures  
  - Pawn promotion
- **Bitboard Representation**: Efficient 64-bit integer representation for board and pieces
- **Piece Move Generation**: Pawns, Knights, Bishops, Rooks, Queens, Kings
- **Board Evaluation**: Material values, positional bonuses, endgame king positioning
- **History Tracking**: Move & position history, FEN generation & loading
- **Utility Functions**: Board rotation, flipping, visualization, and bitboard/notation conversion

</div>

---

<div align="center">

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/python-chess-engine.git
cd python-chess-engine

# Install dependencies (if any)
pip install -r requirements.txt
