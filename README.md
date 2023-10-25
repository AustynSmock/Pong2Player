# Pong 2-Player Game

![Pong Gameplay](pong_screenshot.png)

Pong is a classic 2-player game implemented in Love2D, where two players control paddles to hit a ball back and forth. The objective is to score points by making the ball pass the opponent's paddle.

## Table of Contents
- [Game Features](#game-features)
- [Getting Started](#getting-started)
- [Controls](#controls)
- [Code Overview](#code-overview)

## Game Features

- Two-player gameplay: Play against a friend in local multiplayer mode.
- Score tracking: Keep track of both players' scores.
- Serve and play: Serve the ball and compete for points in each round.
- Victory screen: Celebrate your victory when one player reaches 10 points.

## Getting Started

1. **Prerequisites:**

   Make sure you have [Love2D](https://love2d.org/) installed on your system.

2. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/pong-game.git
   cd pong-game

## Controls

Player 1 (Left Paddle):
- Move Up: W
- Move Down: S

Player 2 (Right Paddle):
- Move Up: Up Arrow Key
- Move Down: Down Arrow Key

General Controls:
- Start/Restart the game: Enter/Return
- Quit the game: Escape

## Code Overview

This game is built using the Love2D framework and consists of multiple Lua scripts:

1. main.lua: This is the main entry point for the Love2D application, containing game setup and the main loop.

2. Ball.lua and Paddle.lua: These files define the Ball and Paddle classes used for game elements. They manage ball movement, collisions, and paddle behavior.

3. push.lua: This script is part of the push library used to handle screen scaling and rendering.
