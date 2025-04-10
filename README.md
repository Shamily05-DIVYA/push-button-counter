*TASK 1- PUSH BUTTON COUNTER*

This project implements a simple push-button counter using a microcontroller in an embedded system. The counter increments each time the push button is pressed and displays the count on a connected LCD display or the Serial Monitor. This project is simulated in **TinkerCAD**, making it easy to visualize the circuit and understand its functionality.

## Features
- **Button Press Counter**: Counts the number of times a button is pressed.
- **Display Output**: Shows the count on a 7-segment display or Serial Monitor.
- **Debouncing**: Prevents multiple counts for a single button press due to noise.
- **Reset Functionality**: Resets the counter to 0 using a secondary button.

## Requirements
- Microcontroller (e.g., Arduino Uno)
- Push button(s)
- LCD display or Serial Monitor
- Resistors (for pull-up or pull-down configuration)
- Breadboard and jumper wires
- Simulation tool: [TinkerCAD](https://www.tinkercad.com/)

## How It Works
1. **Button Detection**: The microcontroller reads the digital state of the button.
2. **Debouncing**: Implemented in software to ensure a stable signal.
3. **Counting**: The counter increments each time the button is pressed.
4. **Displaying Count**: The count is displayed on a LCD display or printed to the Serial Monitor.
5. **Reset**: Optionally, a reset button clears the counter to start from 0.
