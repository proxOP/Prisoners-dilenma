# Strategy Simulation Game

This project simulates a strategy-based game where different strategies compete against each other. The strategies are implemented as players that can either cooperate or backstab in each round, and the outcomes are analyzed based on their cumulative scores.

## Features

- **Multiple Strategies:** Simulates a variety of strategies including always cooperating, always backstabbing, tit-for-tat, grudger, pavlov, randomly defective, detective, and forgiving tit-for-tat.
- **Game Simulation:** Runs multiple rounds of games between pairs of players to determine their cumulative scores.
- **Visualization:** Utilizes Plotly to visualize the results of the simulations, showing cumulative points by strategy and scores per round.

## Requirements

- Python 3.6 or higher
- Plotly
- Pandas

You can install the required libraries using pip:

```bash
pip install plotly pandas
