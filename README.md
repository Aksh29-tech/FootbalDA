# FIFA 20 Player Dataset Analysis

## Project Overview

This project provides an in-depth analysis of the FIFA 20 player dataset. The dataset includes detailed statistics for players from various football clubs worldwide, featuring attributes like player positions, shooting, defending, physical attributes, nationality, wage, and many other performance metrics. The goal of this analysis is to explore and extract insights based on player characteristics and performance metrics across different football clubs and nationalities.

## Project Structure

- **Data File**: `players_20.csv`  
  This file contains detailed data of 18,278 football players and 104 attributes per player, such as personal details (name, nationality, age), physical stats (height, weight), and various performance metrics (shooting, passing, dribbling, defending, etc.).

- **Libraries Used**:
  - `pandas`: For data manipulation and analysis.
  - `matplotlib.pyplot`: For creating static visualizations.
  - `seaborn`: For creating enhanced data visualizations.

## Key Analysis Areas

### 1. Top Nationalities by Player Count
The dataset includes players from 162 different nationalities. The analysis identifies the top 5 nationalities with the highest number of players and visualizes this data.

### 2. Top Earning Players
A detailed list of the top players based on their wage is generated, highlighting the highest earners in the dataset.

### 3. Player Physical Attributes
- Analysis of player height and weight, including identifying the tallest and heaviest players from specific countries (e.g., Germany).

### 4. Player Performance Metrics
- **Shooting**: Sorting players by their shooting ability, highlighting top scorers.
- **Defending**: Sorting players by their defending skills, identifying top defenders.

### 5. Club-Specific Analysis
- Detailed analysis of players belonging to top football clubs, such as Real Madrid. Sorting them by their wage, shooting, and defending stats to understand the club's performance dynamics.

## Dataset Insights

### 1. Nationality Distribution
Players from England, Germany, and Spain make up a significant portion of the dataset, with England having the highest count of players.

### 2. Top Salaries
The top earners are predominantly well-known stars, with Lionel Messi, Eden Hazard, and Cristiano Ronaldo topping the list.

### 3. Physical Traits
The analysis shows that players from Germany tend to be taller and heavier than those from other countries. The dataset identifies several players who stand over 2 meters tall.

### 4. Performance Leaders
Players like Cristiano Ronaldo, Lionel Messi, and Harry Kane are among the highest performers in terms of shooting, while defenders like Giorgio Chiellini and Virgil van Dijk lead the defending rankings.

## Visualizations

The following visualizations have been created in this project:
- **Nationality Distribution Bar Chart**: Visualizes the distribution of players based on nationality.
- **Top Earning Players Bar Chart**: Displays the top 5 players by their wages.
- **Shooting Performance Bar Chart**: Shows a ranking of players based on their shooting ability.
- **Defending Performance Bar Chart**: Highlights the top defenders in the dataset.

## Conclusion

This project presents a comprehensive analysis of FIFA 20 player data, exploring multiple facets of player performance and characteristics. From the top nationalities to performance in shooting and defending, this dataset allows for deep insights into the football world as seen through the lens of FIFA statistics.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - matplotlib
  - seaborn

## Installation

To get started with the project, clone this repository and install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
