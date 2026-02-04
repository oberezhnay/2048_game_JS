# 2048 Game (JavaScript)

A browser-based implementation of the classic **2048 game**, built with **JavaScript**, HTML, and CSS.
This project focuses on **JavaScript logic, state management, and DOM manipulation**.

## 🔗 Live Preview
  - [DEMO LINK](https://oberezhnay.github.io/2048_game_JS/)

## 🎨 Design Reference

The project is inspired by the original **2048 game by Gabriele Cirulli**.
All game logic and UI behavior were implemented independently for educational purposes.

## 🛠 Technologies Used

- **HTML5** — application structure
- **CSS3** — game board styling and tile animations
- **JavaScript (ES6)** — game logic, state handling, and DOM updates
- **Git & GitHub** — version control
- **GitHub Pages** — deployment

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```
git clone https://github.com/oberezhnay/layout_landing-page.git
cd layout_landing-page
```

2. Install dependencies

```
npm install
# or
yarn install
```

3. Run the project locally

```
npm start
# or
yarn start
```

The game logic is implemented without external libraries and includes:

- Game state management using a 4×4 matrix

- Tile movement algorithm for all directions (left, right, up, down)

- Merging logic that prevents multiple merges in a single move

- Random tile generation after each valid move

- Win condition detection (2048 tile)

- Game over detection when no moves are possible

- Score calculation based on merged tiles
