# March Machine Learning Mania 2024 - Predictive Analysis

## Project Overview

This project was submitted as an entry in the Kaggle March Machine Learning Mania 2024. The project focuses on forecasting the outcomes of the NCAA college basketball tournaments for both men's and women's leagues in 2024. Utilizing a combination of historical game data and advanced machine learning techniques, specifically XGBoost, the goal is to predict game outcomes accurately. This endeavor includes a comprehensive ELO model, followed by a detailed feature engineering process to enhance model performance, culminating in a comprehensive analysis that aims to optimize prediction accuracy and submit a bracket prediction for evaluation using the Brier score metric.

## Features

- **Data Preparation and Cleaning:** Utilization of historical NCAA games data, cleaning, and formatting it for analysis.
- **ELO Ranking:** Creation of an ELO ranking system, which dynamically adjusts team ratings based on a number of factors, providing a quantitative measure of team strength that's incorporated into the predictive modeling process.
- **Feature Engineering:** Development of over 60 features per team per season, including team performance metrics and the ELO rankings.
- **Predictive Modeling:** Implementation of XGBoost, a gradient boosting framework, to train a predictive model for game outcomes.
- **Bracket Prediction:** Generation of bracket predictions for both men's and women's tournaments based on model forecasts.
- **Evaluation:** Application of the Brier score metric to assess prediction accuracy and model performance.

## Installation

Ensure you have R and the required packages (`dplyr`, `xgboost`, etc.) installed. Follow these steps to set up the project environment:

1. Clone this repository: `git clone https://github.com/jakesak/march-madness-2024.git`
2. Set the working directory in RStudio or R console to the cloned repository's location.
3. Install any missing R packages by running `install.packages(c("dplyr", "xgboost"))`.

## Usage

Navigate to the `Code` directory and execute the scripts in the following order:

1. `Mensfinal.R` - To run the complete code using one xgboost output.
2. `MensAverageRuns.R` - To run 500 predictions and take the average bracket for smoother predictions.
## Contributing

Contributions to improve the project are welcome. Follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Jacob Sak - [jsak@wisc.edu](mailto:jsak@wisc.edu)

Project Link: [https://github.com/jakesak/March-Madness-Mania-2024](https://github.com/jakesak/March-Madness-Mania-2024)
