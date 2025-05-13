# ♟️ Human vs AI Chess Game – Spring 2025

This project is a simplified Chess game implemented in **Python** with a **Graphical User Interface (GUI)** using **Tkinter**, and an **AI opponent** powered by the **Minimax algorithm**. Developed as part of the *Artificial Intelligence* course (Spring 2025) at the **Department of Cyber Security**.

## 🧠 AI Features
- AI plays against a human using the **Minimax algorithm**.
- Optional **Alpha-Beta Pruning** optimization for deeper and faster search.
- Heuristic evaluation based on:
  - Material advantage
  - King safety
  - Positional strength (e.g., central control)

## 🎮 Game Features
- Turn-based gameplay (Human vs AI)
- Full implementation of standard chess rules, including:
  - Legal move generation for all 6 chess pieces
  - **Check**, **Checkmate**, and **Stalemate** detection
- Move validation to prevent illegal moves

## 🖼️ GUI Features
- Developed with **Tkinter** for interactive gameplay
- Input moves via text box (e.g., `e2e4`)
- Optional highlighting of valid moves
- Clear display of game status (e.g., "Checkmate", "AI is thinking...")

## 🧱 Code Structure
- `ChessGame`: Manages game loop and endgame conditions
- `Board`: Maintains the 8x8 board state
- `Move`: Represents all move types
- `Piece` (abstract base class): Inherited by `King`, `Queen`, `Rook`, `Bishop`, `Knight`, `Pawn`
- `Player` (abstract base class): Inherited by `HumanPlayer` and `AIPlayer`
- `Evaluation`: Contains heuristic evaluation logic

## 🛠️ Technologies Used
- Python 3.x
- Tkinter (GUI)
- abc (Abstract Base Classes)
- copy (deep copy for move simulation)
- time (for AI delay/benchmarking)


