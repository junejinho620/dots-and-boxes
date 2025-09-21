# Dots & Boxes – DE1-SoC

A C implementation of the classic **Dots & Boxes** game on the DE1-SoC, rendered to VGA with PS/2 keyboard input. Two players compete to complete boxes on a grid, and the player with the most boxes at the end wins.

## Overview
- **Platform:** Terasic DE1-SoC FPGA  
- **Language:** C  
- **I/O:** VGA display, PS/2 keyboard  

### Features
- **Interactive Gameplay**: Supports 2 players with real-time score tracking.  
- **Graphics**: VGA rendering of dots, lines, and filled boxes with color-coded ownership (Red vs. Blue).  
- **Controls**:  
  - `W/A/S/D` – Navigate cursor  
  - `[SHIFT]` – Toggle orientation (horizontal/vertical)  
  - `[ENTER]` – Place line  
  - `[SPACE]` – Start or restart game  
- **Scoring**: Automatic detection of completed boxes, with filled color for the player.  

### Impact
- Implemented framebuffer drawing primitives (pixels, lines, grid plotting).  
- Built a **finite-state machine** for seamless transition between game states.  
- Delivered a polished user experience with restart flow and on-screen instructions.  

---

## 🧰 Tech Stack
- **C** on ARM A9  
- **FPGA Peripherals**: VGA controller, PS/2 keyboard interface  

---

## 👥 Contributors  
- **Jinho Choi**  
- **Jin Jung**  
