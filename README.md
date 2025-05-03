# 🔢 Magic Number Game

A fun, interactive number-guessing game built with **React**! Think of a number between 1 and 21, and the app will magically guess it in just **3 steps** using a classic card trick logic.

## ✨ Features

- React-based interactive UI
- Clean and simple design
- Magic number guessing logic using column reordering
- Responsive design
- Restart game functionality

## 🧠 How It Works

1. Think of a number between **1 and 21**.
2. Identify the column that contains your number.
3. Click on that column.
4. Repeat for 3 rounds, and the app will reveal your number!

The trick uses a classic algorithm where the selected column is always placed in the middle, allowing the user's number to converge at the center (11th index) after 3 iterations.

## 🛠️ Tech Stack

- **Frontend:** React
- **Styling:** CSS

## 🚀 Getting Started

Clone the repository and run the app locally:

```bash
git clone https://github.com/yourusername/magic-number-game.git
cd magic-number-game
npm install
npm start
