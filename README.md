<div align="center">

# 🎰 Lottery Game

**A fun, interactive Lottery Game built with React to practice props, state management, and array-based logic.**

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)

[Live Demo](https://lottery-game-pink-gamma.vercel.app/)

</div>

---

## Overview

A lightweight React project built to practice core concepts — props, state management, and array-based logic — through a simple lottery ticket game where numbers are randomly generated and checked against a win condition.

## ✨ Features

- 🎟️ Randomly generates a ticket with a set of numbers
- 🔄 "Buy new Ticket" to generate a fresh set of numbers
- 🏆 Win condition check based on the sum of ticket numbers
- 🎉 Instant win/lose feedback
- 💅 Clean, card-based dark UI

## 🛠️ Tech Stack

- **React.js** – UI library
- **Vite** – Build tool & dev server
- **JavaScript (ES6+)**
- **CSS3**

## 🎮 How It Works

- Each ticket is an array of randomly generated numbers (`n` numbers, default `n = 3`)
- A winning condition function checks whether the sum of the ticket's numbers matches a target value (default target: `15`)
- Clicking "Buy new Ticket" regenerates the numbers and re-checks the win condition

## ⚙️ Getting Started

### Prerequisites
- Node.js and npm

### Installation
```bash
git clone https://github.com/Aditya-Rajpoot/Lottery-Game.git
cd Lottery-Game
npm install
npm run dev
```

The app will be running at `http://localhost:5173`.

## 🚀 Live Demo

🔗 [lottery-game-pink-gamma.vercel.app](https://lottery-game-pink-gamma.vercel.app/)

## 👤 Author

Built by **Aditya Rajpoot**
