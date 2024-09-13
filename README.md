# Tennis Match Prediction

## Project Overview

This project focuses on predicting the outcomes of men's tennis matches using historical data from 2005 to 2019. The dataset was obtained from a reliable betting website, and includes a comprehensive array of data points for each match. The project aims to develop and refine predictive models that can accurately forecast match results based on player rankings and other relevant factors.

## Dataset

The dataset comprises 40,390 entries and 48 columns, representing individual men’s tennis matches from various tournaments. We focused on the data from 2005 to 2019 to ensure consistency and reliability in our analysis. Data prior to 2005 were found to have significant missing information, so it was excluded from the study.

### Selected Columns for Analysis

- **Date**: The date of the match.
- **Tournament**: The name of the tournament where the match took place.
- **Surface**: The type of surface (e.g., clay, hard, grass) on which the match was played.
- **Winner**: The name of the player who won the match.
- **Loser**: The name of the player who lost the match.
- **WRank**: The ATP ranking of the winner.
- **WPts**: The ATP ranking points of the winner.
- **LRank**: The ATP ranking of the loser.
- **LPts**: The ATP ranking points of the loser.
- **B365W**: Bet365 odds of the winner.
- **B365L**: Bet365 odds of the loser.
- **PSW**: Pinnacle Sports odds of the match winner.
- **PSL**: Pinnacle Sports odds of the match loser.
- **higher rank won**: A boolean indicator showing whether the higher-ranked player won the match.
- **diff**: The difference in ATP ranking points between the two players.

### Dataset Source

The dataset was obtained from [Tennis Data](http://www.tennis-data.co.uk/alldata.php).

## Project Structure

- **Betting_data/**: Contains the historical tennis match data from 2000-2020.
- **538_model.ipynb**: Jupyter notebook implementing the 538 model for match prediction.
- **ELO_const_K.ipynb**: Jupyter notebook implementing the ELO model with a constant K-factor.
- **Logistic_Reg.ipynb**: Jupyter notebook implementing Logistic Regression for match prediction.
- **Naive.ipynb**: Jupyter notebook implementing a Naive prediction model.
- **Final_Tennis_report.pdf**: Detailed project report explaining the methodology, models used, and results obtained.

## How to Run the Code

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open any of the Jupyter notebooks (`.ipynb` files) using Jupyter Notebook or Jupyter Lab.
4. Run the cells in the notebook sequentially to reproduce the analysis.

## Project Report

For a detailed explanation of the methodology, data analysis, and results, please refer to the [Final Project Report](./Final_Tennis_report.pdf).

## Contact

For any questions or suggestions, feel free to contact me at [rohan.padaya.rh@gmail.com](mailto:rohan.padaya.rh@gmail.com).
