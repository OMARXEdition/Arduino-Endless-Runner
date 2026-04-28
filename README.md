# Arduino LCD Endless Runner 🏃‍♂️

An embedded systems project featuring a real-time side-scrolling game on a 16x2 LCD. This project utilizes hardware interrupts for responsive gameplay and custom CGRAM character generation.

### 1. Initialization State
![Start Screen](Assets/Screenshot%202026-04-28%20062249.png)
*Figure 1: The Idle state prompted by the "Press Start" routine.*

### 2. Active Gameplay
![Active Action](Assets/Screenshot%202026-04-28%20061628.png)
*Figure 2: Real-time rendering of the hero sprite jumping over an obstacle.*

### 3. Game Over & Reset
![End State](Assets/Screenshot%202026-04-28%20061741.png)
*Figure 3: System halt after collision detection, displaying the final score.*

##  Technical Features
- **Interrupt Service Routine (ISR):** Uses hardware interrupts on Pin 2 for zero-latency jump input.
- **Finite State Machine (FSM):** Manages game states (Idle, Playing, Game Over).
- **Custom Bitmaps:** 7 unique 5x8 pixel sprites created via CGRAM.
- **Efficient Scoring:** Bit-shifted distance tracking for optimized performance.

##  Hardware Setup
- Arduino Uno / Nano
- 16x2 LCD Display (Parallel interface)
- Tactile Push Button
- 10k Potentiometer (for Contrast)
