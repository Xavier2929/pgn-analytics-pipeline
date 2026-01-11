# pgn-analytics-pipeline

This analytics pipeline, is a predecesor of the twic pipeline, which it's purpose is to pass pgn-chess-games to a postgress db that will be used for analytics.

## 🚀 Tech Stack

- Python 3.12.4
- Postrgress

## 📦 Requirements

- Python 3.10+
- SQL

## ⚙️ Instalations

- have the required python version.
- run the venv
- run the requirements txt file with pip install -r requirements.txt
- Have a postgress instance running and install the database given.

## 🏅 Milestones

- parse basic data from a chess game (moves, players, results, opening name)
- insert data in db
- make a trigger that checks if the game that's gonna be imported, isn't a duplicated one / empty one
- get games with a specific pawn structure/formation
