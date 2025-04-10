# Chudnovsky Algorithm for π in PenguinMod

This project implements the Chudnovsky algorithm for calculating π to high precision using PenguinMod with the Infinity addon. The Chudnovsky algorithm is one of the most efficient methods for calculating π and has been used to set several world records for π computation.

## About the Chudnovsky Algorithm

The Chudnovsky algorithm is based on the following formula:

```
1/π = 12 * Σ ((-1)^k * (6k)! * (13591409 + 545140134k) / ((3k)! * (k!)^3 * 640320^(3k+3/2)))
```

Where the summation runs from k=0 to infinity.

## How to Use

1. Open PenguinMod (https://penguinmod.site/)
2. Make sure you have the Infinity addon installed
3. Import the .pmp file from this repository
4. Run the project to calculate π to high precision
5. Adjust the number of iterations to control precision and computation time

## Features

- Implementation of the Chudnovsky algorithm
- Large number arithmetic operations
- User interface to display results and control iterations
- Visualization of the calculation process

## Requirements

- PenguinMod
- Infinity addon

## Notes

The calculation speed depends on your computer's processing power. Higher precision (more iterations) will require more computation time.