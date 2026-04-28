# Arduino LCD Endless Runner 🏃‍♂️

An embedded systems project featuring a real-time side-scrolling game on a 16x2 LCD. This project utilizes hardware interrupts for responsive gameplay and custom CGRAM character generation.

## 📸 Hardware Preview
![Start Screen](Assets/Screenshot%202026-04-28%20061730.jpg)
*Figure 1: Initial idle state with "Press Start" prompt.*

![Gameplay](Assets/Screenshot%202026-04-28%20061628.jpg)
*Figure 2: Active gameplay demonstrating jump mechanics and score tracking.*

## 🚀 Technical Features
- **Interrupt Service Routine (ISR):** Uses hardware interrupts on Pin 2 for zero-latency jump input.
- **Finite State Machine (FSM):** Manages game states (Idle, Playing, Game Over).
- **Custom Bitmaps:** 7 unique 5x8 pixel sprites created via CGRAM.
- **Efficient Scoring:** Bit-shifted distance tracking for optimized performance.

## 🛠️ Hardware Setup
- Arduino Uno / Nano
- 16x2 LCD Display (Parallel interface)
- Tactile Push Button
- 10k Potentiometer (for Contrast)
