# Prison Escape Game

## Overview

  Prison Escape is a 2D console-based action game where the player controls a prisoner trying to escape from a high-security prison. The player must defeat various enemies, including a guard, officer, special guard, and a boss, to win the game. The game features multiple characters, weapons, and interaction rules that make the escape challenging and fun.

## Game Characters

  - **Player**: A prisoner with 100% health. The player must defeat enemies to escape the prison.
  - **Enemies**:
    - **Guard**: 100% health, highest fire rate, lowest health.
    - **Officer**: 150% health, medium fire rate and health.
    - **Special Guard**: 200% health, lowest fire rate, highest health.
    - **Boss**: 500% health, fires in all directions. Appears after killing 2 enemies.

## Game Objects

  - **Health Increment**: The player gains a health boost (+100%) when collecting a shield dropped by a special guard.
  - **Weapons**:
    - **G**: Gun with a low fire rate (fires 1 bullet at a time).
    - **M**: Machine gun with continuous fire.

## Rules & Interactions

  1. Avoid enemy bullets that decrease the player’s health.
  2. Kill all enemies, including the boss, to win the game.
  3. The game can be paused by pressing the left shift key and resumed by pressing the right shift key.
  4. The player must collect guns ('G' or 'M') to start shooting.

## Goal

  Escape the prison by defeating all enemies and obtaining a key from the boss to open the door and then escaping the jail.

## How to Use
**Clone the Repository**:
   - Clone the repository to your local machine using Git:
     ```bash
     git clone https://github.com/aabr2612/Prison-Escape.git
     ```
   - Run the Executable: Double-click to launch the game.

## Conclusion

  The Prison Escape game project helped me strengthen my programming skills. It was a great learning experience in game development, logic building, and problem-solving.