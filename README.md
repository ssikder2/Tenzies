# [Click here to play!](tenzies-rho-seven.vercel.app/)

# Tenzies Game

Tenzies is an interactive dice game built using React. The goal of the game is to roll the dice until all of them show the same number. Players can hold dice to prevent them from being rerolled, adding a layer of strategy to the gameplay.

---

## Features

- **Interactive Gameplay**: Click on dice to hold or release them.
- **State Management**: Dice values and held states are managed dynamically using React state.
- **Winning Condition**: Displays a win message when all dice are held and show the same number.

---

## How to Play

1. Roll all the dice.
2. Click on a die to "hold" its value. Held dice will not change when rerolled.
3. Continue rolling until all dice show the same number.
4. Win the game and see the "Game Won!" message!

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ssikder2/Tenzies.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Tenzies
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the game in your browser at [http://localhost:3000](http://localhost:3000).

---

## Project Structure

```
Tenzies/
├── public/
├── src/
│   ├── components/
│   │   ├── Die.jsx
│   │   └── App.jsx
│   ├── App.css
│   └── index.jsx
├── .gitignore
├── package.json
└── README.md
```

- **`components/Die.jsx`**: Contains the logic for individual dice.
- **`App.jsx`**: Main component that renders the game.
- **`App.css`**: Styles for the game interface.

---

## Technologies Used

- **React**: For building the user interface.
- **CSS**: For styling the game.
- **JavaScript**: For handling logic and interactivity.

---

## Future Improvements

- Add a timer to track how quickly the player wins.
- Implement a scoring system to add competitiveness.
- Include additional visual effects for dice rolls and winning.
- Make the game mobile-friendly with responsive design.

---

## Credits

This project was built as part of the Scrimba React course. Special thanks to Scrimba for their amazing learning resources!
