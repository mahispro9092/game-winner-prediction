# Game Winner Prediction - PUBG

This project focuses on predicting the winning probability (`winPlacePerc`) in PUBG matches using gameplay statistics. The solution involves comprehensive data analysis, feature engineering, model development, and evaluation to identify the best-performing approach.

## Project Structure

- `PRCP-1012-Game Winner Prediction Final PTID-CDS-FEB-25-2431.ipynb`: Jupyter Notebook containing complete code, data analysis, visualizations, model building, and evaluation.
- `PRCP-1012-GameWinnerPred.docx`: Problem statement document provided for the project.
- `README.md`: Project overview, setup instructions, and details.

## Objective

1. Analyze PUBG gameplay data to identify patterns and impactful features.
2. Build regression models to predict `winPlacePerc` (win probability).
3. Compare performance across different models and choose the best one.
4. Document challenges faced and solutions implemented.

### Features Used

The dataset includes features like:
- Player stats: `kills`, `assists`, `damageDealt`, `walkDistance`, `rideDistance`, etc.
- Match metadata: `matchType`, `matchDuration`, `maxPlace`, etc.
- Outcome variable: `winPlacePerc`

## Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (for ML models)

## Model Evaluation

The following models were tested:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

Model performance was compared using evaluation metrics like RMSE and R² Score. The best model was selected based on accuracy and generalization capability.

## Challenges Faced

- Handling missing values in gameplay statistics
- Normalizing skewed distributions in continuous variables
- Dealing with outliers
- Choosing appropriate models and preventing overfitting

## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/mahispro9092/game-winner-prediction.git
   ```
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook file:
   ```
   jupyter notebook PRCP-1012-Game\ Winner\ Prediction\ Final\ PTID-CDS-FEB-25-2431.ipynb
   ```
