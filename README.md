# Football Championship 2023 Shot Analysis

This repository contains a Python script designed to analyze shot data from the Football Championship 2023. The script evaluates player and team efficiency, examines the effects of pressure and distance on shot success, and investigates the influence of game timing on shooting decisions and outcomes.

## Overview

The analysis focuses on several key areas:

- **Team and Player Efficiency**: Calculating the success rate of shots for each player and team.
- **Risk Aversion**: Analyzing tendencies towards shooting from distance vs. closer shots under pressure.
- **Game Minute Effect**: Studying how the timing within the game affects shot selection and success.
- **Distance vs. Pressure**: Comparing the effectiveness of shooting from a distance with no pressure vs. shooting closer with pressure.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- Pandas library
- OpenPyXL library (for handling Excel files)

### Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/fechinmitchell/CMC_GAA_STATS.git
```

Navigate to the cloned repository:

```bash
cd CMC_GAA_STATS
```

### Usage

1. Place your dataset (`Football_Championship_2023_Shots.xlsx`) in the root directory of the cloned repository.
2. Open the `analysis_script.py` file in your preferred Python environment or editor.
3. Modify the script to point to your dataset file if necessary.
4. Run the script to perform the analysis.

## Analysis Details

The script performs the following analyses:

1. **Efficiency Calculation**: Measures the number of successful shots over total attempts for both teams and players.
2. **Risk Aversion Analysis**: Assesses player decisions on shot distance under varying pressure levels.
3. **Game Minute Effect Study**: Evaluates how shot success and decisions vary throughout the game.
4. **Distance vs. Pressure Evaluation**: Compares the success rates of shots taken from distance without pressure to those taken closer with pressure.

## Contributing

Contributions to improve the analysis or extend its capabilities are welcome. Please feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to all the players and teams who participated in the Football Championship 2023, making this analysis possible.
- Appreciation to the data collection team for their meticulous effort in capturing detailed shot data.
