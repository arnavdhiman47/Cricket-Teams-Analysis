# Cricket-Teams-Analysis

## Overview
This project analyzes One Day International (ODI) cricket match data to gain insights into various factors affecting match outcomes, such as win/loss ratios, toss results, and victory margins. The analysis is based on historical match data, and the results are intended to help understand team performance in ODI cricket.

## Technologies Used
- **Python**: The primary programming language for data analysis and manipulation.
- **Pandas**: Used for data manipulation, cleaning, and analysis.
- **NumPy**: Utilized for numerical operations and calculations.
- **Matplotlib**: Used for creating visualizations of data (charts and graphs).
- **Seaborn**: For advanced statistical visualizations.
- **Jupyter Notebook**: The interactive environment used to develop and execute the code.
- **Anaconda**: The distribution used for managing Python packages and environments.

## Dataset
The dataset used in this project is the `ODI_Match_Results.csv`, which contains historical ODI match results with columns including:
- `Norm_ID`: Unique identifier for each match result.
- `Result`: Outcome of the match (won/lost).
- `Margin`: Margin by which the match was won or lost.
- `Toss`: Result of the toss (won/lost).
- `Bat`: Whether the team batted first or second.
- `Opposition`: Opposing team.
- `Ground`: Location of the match.
- `Start Date`: Date of the match.
- `Match_ID`: Official match identifier.
- `Country`: Team being analyzed.
- `Country_ID`: Unique identifier for the country.

## Analysis
1. **Win/Loss Analysis**: Calculate and visualize the win percentages for different teams based on match results.
2. **Toss Impact**: Analyze the effect of toss outcomes on match results to understand if winning the toss significantly affects winning the match.
3. **Margin of Victory Analysis**: Investigate the margin of victory based on whether a team batted first or second to identify trends in match outcomes.

## Getting Started
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Cricket-Teams-Analysis.git
   cd Cricket-Teams-Analysis
**Future Work**
Complete the analysis of victory margins to identify if teams batting first tend to win by larger margins.
Incorporate machine learning models to predict match outcomes based on historical data.
Extend the analysis to include player performance and team dynamics.
**License**
This project is licensed under the MIT License. See the LICENSE file for details.


