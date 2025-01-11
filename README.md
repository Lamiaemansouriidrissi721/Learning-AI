🎰🤖 Multi-Armed Bandit Simulation with Beta Distribution 🤖🎰
Project Overview

This project simulates a Multi-Armed Bandit (MAB) problem, a classic scenario in probability theory and decision-making. The objective is to maximize cumulative rewards by selecting the most optimal "slot machine" (bandit) over time. The simulation employs Beta distribution to model the probability of success for each bandit, facilitating a balance between exploration and exploitation.
GeeksforGeeks
Purpose

The primary goal is to demonstrate the application of Beta distribution in solving the MAB problem. By simulating multiple bandits with varying success probabilities, the project aims to identify the most rewarding bandit through iterative trials.
Key Features

    Simulation of Multiple Bandits: Modeling several slot machines, each with a distinct probability of yielding a reward.
    Beta Distribution Application: Utilizing Beta distribution to represent the uncertainty in each bandit's success probability.
    Iterative Selection Process: Implementing a strategy to select bandits based on their estimated success probabilities, updating beliefs after each trial.
    Performance Tracking: Recording the number of times each bandit is selected and the cumulative rewards obtained.

Data Sources

    Simulated Data: The project generates synthetic data representing the success probabilities of each bandit.

Installation and Setup

    Install Python: Ensure Python 3.x is installed on your system.
    Install NumPy: Install the NumPy library using pip:

    pip install numpy

    Run the Script: Execute the Python script to simulate the MAB problem and observe the results.

Usage

    Run the Simulation: Execute the script to simulate the selection process of the bandits.
    Analyze Results: Review the output to identify which bandit was selected most frequently and assess the cumulative rewards.
