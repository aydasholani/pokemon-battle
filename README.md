# Pokémon Battle

This project analyzes Pokémon battle outcomes using data from the [Complete Pokémon Dataset](https://www.kaggle.com/datasets/kylekohnen/complete-pokemon-data-set). The goal is to track victories, analyze battle patterns, and identify the top-performing Pokémon based on historical battles.

## Features

- **Battle Analysis**: The script groups Pokémon by their battle victories and allows easy comparison between the top and bottom performers.
- **Data Cleaning**: Includes steps for cleaning the data and preparing it for analysis.
- **Visualization**: Data is visualized using charts to display the top 10 and bottom 10 Pokémon by victories.
- **Machine Learning (Future)**: Plans to implement machine learning to predict battle outcomes.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aydasholani/pokemon-battle.git
   cd pokemon-battle
   ```

2. Install the required packages:

   ```bash
   conda create --name <env> python=3.8.19
   conda activate <env>
   conda install --file req.txt
   ```