# ATM-SIMULATOR

## Overview

This Python project implements a simple ATM Simulator, allowing users to perform basic banking transactions such as checking balance, withdrawing, depositing, and exiting. The application is designed with a class-based structure for managing ATM functionalities.

## Project Structure

- `atm_simulation.ipynb`: Contains the implementation of the `ATMSimulator` class and the main logic for user interaction.
- `README.md`: This file, providing an overview of the project, instructions, and details.

## Usage

1. Open the `atm_simulation.ipynb` in a Python environment.
2. Run the notebook to start the ATM Simulator.
3. Enter the PIN when prompted.
4. Choose from the available options: Balance, Withdraw, Deposit, or Exit.

## Code Structure

- `ATMSimulator` class:
  - `__init__`: Initializes the ATM with a default balance.
  - `check_balance`: Displays the current balance.
  - `withdraw_amount`: Allows the user to withdraw money, handling insufficient balance.
  - `deposit_amount`: Allows the user to deposit money.

- `main` function:
  - Handles user interaction, PIN verification, and option selection.

## Important Note

- For simplicity, the correct PIN is hardcoded. In a real-world scenario, implement secure PIN handling.
- The initial balance is set to Rs. 10,000 for demonstration purposes.

## Contributors

- Pooja yadav


