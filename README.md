# Brick Breaker Game

A classic Brick Breaker game implemented in Java using Swing.

## Features

- 3 progressively challenging levels
- Power-up system with speed boosts
- Different point values for different colored bricks
- Pause/Resume functionality
- Score tracking
- Keyboard controls

## Controls

- **Left Arrow**: Move paddle left
- **Right Arrow**: Move paddle right
- **P**: Pause/Resume game
- **R**: Restart game

## Power-ups

- White dots on bricks indicate speed power-ups
- Collecting a power-up increases ball speed by 50% for 5 seconds
- Ball turns yellow when speed boost is active

## Scoring

Points per brick (multiplied by current level):
- Red bricks: 50 points
- Orange bricks: 40 points
- Yellow bricks: 30 points
- Green bricks: 20 points
- Blue bricks: 10 points

## How to Run

1. Make sure you have Java installed on your system
2. Compile the game:
   ```bash
   javac *.java
   ```
3. Run the game:
   ```bash
   java BrickBreaker
   ```

## Game Features

- Progressive difficulty across levels
- More rows of bricks in higher levels
- Increased chance of power-ups in higher levels
- Higher scoring potential in higher levels
- Victory screen upon completing all levels

## Files

- `BrickBreaker.java` - Main entry point
- `GamePanel.java` - Main game logic and rendering
- `Ball.java` - Ball physics and movement
- `Brick.java` - Brick properties and rendering
- `Paddle.java` - Paddle movement and controls 