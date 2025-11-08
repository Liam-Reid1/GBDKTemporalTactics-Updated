Updated version of the GBDK project Temporal Tactics using GBDK v4.4.0

# Temporal Tactics (GBDK-2020)

A retro Game Boy project built using **GBDK-2020 v4.4.0**.  
This project includes custom sprites, background tiles, and gameplay logic written in C.

---

## Overview

This project is a simple custom made Game Boy ROM 
It runs on the original Game Boy hardware or any compatible emulator.

**How To Play**
Use 'A' to move forward
Use 'B' to shoot
Use the directions to change what way to face
Use 'START' to begin/replay the game
Use 'SELECT' to switch colour palettes

Shoot the target and get to the goal without running out of moves. 
Each round creates a duplicate of your ship that performs the actions you made in the previous round.
Avoid crashing and/or shooting a version of your ship.

---

## Requirements

- [GBDK-2020](https://github.com/gbdk-2020/gbdk-2020) v4.4.0 or later  
- Windows, macOS, or Linux terminal
- (Optional) Emulator such as [mGBA](https://mgba.io/) or [BGB](https://bgb.bircd.org/)

---

## Building the Game

1. Install GBDK-2020 and make sure it’s in your system `PATH`.
2. Clone or download this repository.
3. Open a terminal in the project folder and run:

   ```bash
   make

   ```
Once complete, the updated TemporalTactics.gb file will be created.
