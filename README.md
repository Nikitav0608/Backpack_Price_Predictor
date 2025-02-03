# Backpack Price Predictor

## Overview
Backpack Price Predictor is a machine learning project that uses Linear Regression to estimate the price of backpacks based on various features. The dataset consists of 3 lakh rows and 10 columns, and the project includes a complete Exploratory Data Analysis (EDA) to understand feature importance and relationships.

## Features
- **Data Size**: 3,00,000 rows, 10 columns
- **Algorithm Used**: Linear Regression
- **Libraries Used**: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Exploratory Data Analysis (EDA)**: Conducted to analyze feature distributions, correlations, and patterns

## Project Structure
```bash
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks for EDA & model training
├── src/                 # Source code for model training & evaluation
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/backpack_price_predictor.git
   cd backpack_price_predictor
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the EDA notebook to explore the dataset.
2. Train the Linear Regression model using the training script.
3. Evaluate the model's performance on the test dataset.

## Results
- Achieved a reasonable prediction accuracy using Linear Regression.
- Identified key factors influencing backpack prices.
- Optimized the model using feature engineering and hyperparameter tuning.

## Future Enhancements
- Implement other regression models (e.g., Decision Tree, Random Forest, XGBoost) for comparison.
- Deploy the model using Flask or Streamlit.
- Improve feature selection and engineering.

## License
This project is licensed under the MIT License.

## Author
[Your Name]

