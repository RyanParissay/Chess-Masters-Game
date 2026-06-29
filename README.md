# ♛ Chess Masters Game

A single-file browser chess game where **you play White against a built-in computer opponent**. No installation, no dependencies — just open `index.html` in your web browser.

## How to play

1. Open `index.html` (double-click it, or drag it into a browser).
2. You are **White** (bottom of the board). Click one of your pieces — the squares you can move to light up.
3. Click a highlighted square to move. The computer replies automatically.
4. Pick a **difficulty** (Easy / Normal / Hard) and use **New Game** or **Undo** anytime.

## Features

- Full legal-move enforcement: castling, en passant, and pawn promotion
- Check, checkmate, and stalemate detection
- Legal-move highlighting and last-move / check indicators
- Captured-piece trays for both sides
- A basic AI opponent (minimax search with alpha–beta pruning and piece-square evaluation)

## Notes

- Pawns auto-promote to a Queen.
- The AI is intentionally lightweight — fun to play, not grandmaster strength.

Built with plain HTML, CSS, and JavaScript.
