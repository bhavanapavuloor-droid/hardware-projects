# Traffic Lights

A traffic signal simulation built on Wokwi using an Arduino. Three LEDs (red, yellow, green) cycle in the same order as a real signal.

![Circuit](circuit.png)

**Simulation:** [https://wokwi.com/projects/475599620231189505]

## Components
- Arduino Uno
- 3 LEDs (red, yellow, green)
- 3 resistors ([220 Ω])
- Breadboard and jumper wires

## Pin connections
| LED    | Arduino pin |
|--------|-------------|
| Red    | [pin 8]     |
| Yellow | [pin 9]     |
| Green  | [pin 10]    |

## How it works
1. Red stays on for [5] seconds.
2. Green stays on for [5] seconds.
3. Yellow stays on for [2] seconds.
4. The cycle repeats forever.

Each LED is set as an output with `pinMode()` and switched with `digitalWrite()`. The timing uses `delay()`.

## What I learned
- Controlling multiple outputs from one program
- Why LEDs need a current-limiting resistor
- Planning a sequence of states in code

## Ideas to improve
- Add a pedestrian button
- Replace `delay()` with `millis()` for non-blocking timing