
# Economic Simulation Model

## Overview
This project is a Python-based economic simulation model that includes a banking system, loans, investments, and individual agents producing and consuming goods. The model is designed to analyze how different economic factors influence financial transactions and economic growth.

## Features
- **Banking System:** Manages deposits, loans, and interest rates.
- **Loan System:** Individuals can take loans and repay them with interest.
- **Investment Mechanism:** People can invest in businesses or other assets.
- **Production & Consumption:** Agents produce and consume goods, influencing prices.
- **Utility Function:** Determines economic well-being based on production and consumption.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib
- SciPy

Install dependencies using:
```bash
pip install numpy matplotlib scipy
```

## Usage
1. Run the simulation:
   ```bash
   python simulation.py
   ```
2. Adjust parameters in the script to test different economic scenarios.

## Code Structure
- `bank.py` - Defines the bank system and loan logic.
- `investment.py` - Handles investments and returns.
- `person.py` - Defines individual economic agents.
- `simulation.py` - Runs the main economic simulation.

## Issues & Improvements
- **Loan Default Handling:** Improve default threshold logic.
- **Investment Returns:** Optimize profit calculation.
- **Price Stability:** Implement dynamic adjustments.

## Contributing
Feel free to submit pull requests to improve the model or add new features.

## License
This project is open-source under the MIT License.

