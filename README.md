# Breakout Game

A simple, lightweight Breakout-style game built using HTML, CSS and JavaScript.

![Gameplay Screenshot](./Screenshot%202026-04-24%20at%2020.18.23.png)

## Demo
- Open `index.html` in your browser to play.
- If you prefer a local server (recommended for some browsers), run:
  - Python 3: `python -m http.server 8000`
  - Then open `http://localhost:8000` in your browser.

## How to Play
- Move the paddle with your mouse. The paddle follows the horizontal position of the cursor.
- Bounce the ball off the paddle to hit and break all the bricks.
- Each broken brick increases your score.
- If you clear all bricks: you win!
- If the ball misses the paddle and hits the bottom: Game Over.

## Controls
- Mouse: Move paddle left/right.

## Files
- `index.html` �� Game canvas and page markup.
- `style.css` — Minimal styling and layout.
- `script.js` — Game logic (ball, paddle, bricks, collision detection, scoring).
- `Screenshot 2026-04-24 at 20.18.23.png` — Screenshot used in this README.

## Customize
You can tweak gameplay by editing values in `script.js`:
- `ballRadius`, `dx`, `dy` — ball size and velocity.
- `paddleWidth`, `paddleHeight` — paddle dimensions.
- `rowCount`, `columnCount`, `brickWidth`, `brickHeight`, `brickPadding` — brick layout.

## Contributing
Contributions are welcome! If you find a bug, or want to add features (lives, levels, sounds, mobile touch controls), open an issue or submit a pull request.

## License
This project is provided as-is. Feel free to fork and use it for learning or personal projects.
