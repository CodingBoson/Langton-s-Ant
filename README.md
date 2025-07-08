# Langton's Ant 🐜

A simple interactive simulation of [Langton's Ant](https://en.wikipedia.org/wiki/Langton%27s_ant) built with HTML5 Canvas and JavaScript.

## Features

- Visualizes the classic Langton's Ant cellular automaton
- Adjustable simulation speed
- Add multiple ants
- Toggle grid overlay

## Usage

1. Open `src/index.html` in your browser.
2. Use the controls to:
    - Adjust speed with the slider
    - Add more ants with the "Add Ant" button
    - Toggle the grid overlay

## Project Structure

```
/src
  └── index.html   # Main simulation and UI
README.md          # Project documentation
```

## How It Works

- The ant moves on a grid of black and white cells.
- At each step:
  - Turns right on a white cell, left on a black cell
  - Flips the color of the cell
  - Moves forward
- The simulation wraps around the edges.

## License

MIT License

---

Made for fun and science! 🐜✨