🎲 Random Simulator – Dice & Coin Toss

A simple probability simulation project that visualizes dice rolls and coin tosses using histograms.
This project demonstrates randomness, distribution patterns, and Monte-Carlo style simulations using NumPy and Matplotlib.

🧠 Concept Diagram (ASCII Explanation)
🎲 Dice Roll Simulation
            Dice (6-sided)
               _______
              |   ●   |
              | ●   ● |
              |_______|
                   ↓ (roll 1000 times)
  -------------------------------------------------
  Outcome: 1  2  3  4  5  6
  Count:   ███ █████ ████ ███ ██ ████  (Histogram)
  -------------------------------------------------

🪙 Coin Toss Simulation
                Coin
        -------------------
        | Heads | Tails   |
        -------------------
                ↓ (toss 1000 times)
  ---------------------------------------
  Outcome: 0 (Tails) | 1 (Heads)
  Count:   ████████  |   ████████
  ---------------------------------------

📌 Project Overview

This mini project contains two probability simulations:

1️⃣ Dice Roll Simulation

Rolls a 6-sided dice 1000 times

Shows how frequently each number (1–6) appears

Demonstrates uniform distribution behavior

2️⃣ Coin Toss Simulation

Tosses a coin 1000 times

Counts Heads (1) and Tails (0)

Demonstrates Bernoulli distribution behavior

🛠️ Technologies Used

Python 3.x

NumPy → for generating random values

Matplotlib → for histogram visualization

📂 Project Structure
Random-Simulator/
│
├── simulator.py        # Main simulation code
└── README.md           # Documentation
