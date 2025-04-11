# Chudnovsky Algorithm for π in PenguinMod

This project implements the Chudnovsky algorithm for calculating π to high precision using PenguinMod with the Infinity addon. The Chudnovsky algorithm is one of the most efficient methods for calculating π and has been used to set several world records for π computation.

## About the Chudnovsky Algorithm

The Chudnovsky algorithm is based on the following formula:

```
1/π = 12 * Σ ((-1)^k * (6k)! * (13591409 + 545140134k) / ((3k)! * (k!)^3 * 640320^(3k+3/2)))
```

Where the summation runs from k=0 to infinity.

## Installation

1. Visit PenguinMod at https://penguinmod.com/
2. Click on the "Add Extension" button (puzzle piece icon)
3. Search for "Infinity" in the extension library
4. Click "Add" to install the Infinity addon
5. Verify the installation by checking if the Infinity blocks appear in your blocks palette

## How to Use

1. Open PenguinMod and create a new project
2. Add the Infinity addon as described in the Installation section
3. Create variables for storing intermediate calculations
4. Implement the Chudnovsky algorithm using the formula provided above
5. Add a slider variable to control the number of iterations
6. Create a loop to perform the calculations based on the iteration count
7. Display the calculated value of π
8. Click the green flag to start the calculation
9. Adjust the slider to control precision (more iterations = higher precision)

## Features

- Implementation of the Chudnovsky algorithm using Infinity addon's mathematical capabilities
- Support for large number arithmetic operations including:
  - Factorial calculations (n!)
  - Arbitrary precision arithmetic
  - Root functions for the denominator calculation
- Interactive user interface to display results and control iterations
- Real-time visualization of the calculation process

## Requirements

- PenguinMod (latest version)
- Infinity addon
- A modern web browser (Chrome, Firefox, Safari, or Edge)

## Notes

- The calculation speed depends on your computer's processing power
- Higher precision (more iterations) will require more computation time
- The Infinity addon handles all large number calculations internally to maintain precision
- Results are displayed with scientific notation for very large numbers