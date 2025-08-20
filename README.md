# Rock-paper-scissors
# Rock Paper Scissors – FreeCodeCamp ML Project

## Overview
This repository contains my solution to the freeCodeCamp Rock Paper Scissors challenge as part of the Machine Learning with Python curriculum.

## Instructions
- The key file **RPS.py** includes my implementation of the `player` function.
- The bot adapts its strategy based on the current opponent (Quincy, Abbey, Kris, Mrugesh) to achieve over 60% win rate for each.

## How the Solution Works
- **Quincy**: The bot detects and counters Quincy's repeating pattern.
- **Abbey**: Uses a 3-gram Markov pattern with limited memory (optimal against Abbey's 2-gram approach).
- **Kris**: Rotates between choices and adds randomness to prevent being countered.
- **Mrugesh**: Manipulates its own move frequencies to beat Mrugesh's frequency analysis.

## How to Run
1. Upload all files to your coding platform or local workspace.
2. Run the tests via `main.py` or using your platform’s built-in test runner.
3. Check results against all four bots.

## Submission
Copy this repository’s link and paste it into the submission box on freeCodeCamp when prompted.

---

**Created by**: [Karan Gayake]
