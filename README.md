# Bagha Chheli (Tiger and Goat)

A complete web-based implementation of the traditional strategy game Bagha Chheli. Built with React, Node.js, and PostgreSQL.

## Features
- **Smart AI**: Minimax algorithm with Alpha-Beta pruning.
- **Multiple Modes**: Player vs Player, Player vs AI, AI vs AI.
- **Classic Rules**: 5 Tigers, 20 Goats. Place Tigers first, then place Goats. Tigers capture by jumping. Goats win by trapping all tigers.
- **Modern UI**: "Ghost Structure" design system, high-fidelity SaaS look.
- **Global Leaderboard**: Track your wins, average moves, and captured goats.
- **Match History**: Review past games.

## Rules
- 5 Tigers are placed on the board first.
- 20 Goats are placed one by one.
- Tigers can capture a goat by jumping over it to an empty space.
- Tigers win if they capture 5 goats.
- Goats win if they completely trap all tigers so they have no legal moves.

## Tech Stack
- Frontend: React, Tailwind CSS, Lucide Icons
- Backend: Node.js API Routes
- Database: PostgreSQL (Neon Serverless)
