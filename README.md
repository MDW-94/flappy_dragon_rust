# Flappy Dragon Game (Rust)

![alt text](<Screenshot 2026-08-18 at 19.40.41.png>)

A simple game built from the <i>Hands-on Rust</i> book by Herbet Wolverson. The game requires the player to press `SPACEBAR` in order to keep the `@` from falling off the screen.

Obstacles start to appear and the player must fly through the gap between them in order to score a point.

If the player hits the bottom of the screen or hits an obstacle they will lose.

## Setup

### Prerequisites:

- Have rust installed locally (on your computer)

### Run Game Locally:

```sh
git clone <gh_repository>
cd ./<gh_repository>
cargo run
```

## Dependencies

- [`bracket-lib`](https://github.com/amethyst/bracket-lib)

## Making Of

...

## Improvements:

- Experiment with gravity level, velocity changes, and game speed
- Add graphics for the walls and dragon
- Consider making the graphics bigger and the overall play area smaller
- Investigate bracket-lib's "flexible console" and change the player coordinates to floating-point numbers for smoother movement
- Add color and visual flair to the menus
- Try animating the dragon
- Refactor codebase and move `Structs` and types implementations (`impl`) to designated files/directories
- Make it so if the player flies to high they will lose
