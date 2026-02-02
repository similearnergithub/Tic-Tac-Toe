# ❌⭕ Tic-Tac-Toe Game using Minimax Algorithm

A Python-based **Tic-Tac-Toe game solver** implemented using the **Minimax algorithm with Alpha-Beta Pruning**, enhanced with **step-by-step board visualization** to demonstrate how optimal decisions are made.

---

## 📌 Project Overview

This project simulates the game of Tic-Tac-Toe where the computer plays optimally against an opponent using **game theory**. The implementation explores all possible legal moves and selects the best one based on the Minimax strategy while reducing unnecessary computations using **alpha-beta pruning**.

---

## 🧠 Core Concepts Used

- Game State Evaluation  
- Minimax Decision Algorithm  
- Alpha-Beta Pruning Optimization  
- Recursive Tree Search  
- Game Termination Detection  
- Visualization of Game States  

---

## ⚙️ How the Game Works

- The board is represented as a **1D NumPy array of size 9**
  - `1` → Computer (X)
  - `-1` → Opponent (O)
  - `0` → Empty cell
- The algorithm:
  1. Checks if the game is terminated (win, loss, or draw)
  2. Finds all legal moves
  3. Recursively evaluates future game states
  4. Uses alpha-beta pruning to skip suboptimal branches
  5. Selects the move leading to the best possible outcome

---

## 🧪 Key Functions

- `check_if_terminated(state)`  
  Detects win, loss, draw, or ongoing game

- `find_all_legal_moves(state)`  
  Returns all valid moves for the current board state

- `visualize_board(state)`  
  Displays the board both in text and graphically using Matplotlib

- `minimax_pruned_with_visualization()`  
  Implements Minimax with Alpha-Beta pruning and visualizes each explored move

---

## 🛠️ Tech Stack

- Python 🐍  
- NumPy (state representation & computations)  
- Matplotlib (board visualization)  
- Math (algorithmic calculations)
  

## 📊 Visualization

- Each possible move explored by the algorithm is visualized
- Uses **Matplotlib** to display the board state
- Helps understand:
  - Decision paths
  - Pruned branches
  - Optimal strategy selection

---

## 🚀 Output

- Returns the **optimal move index**
- Displays the total number of evaluated moves
- Shows the full decision process visually


