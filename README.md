# Linear Regression on Weather Data

This project applies Linear Regression to a historical weather dataset
to predict Temperature (C).

## Dataset
- Source: Kaggle (weatherHistory.csv)
- Missing values are removed
- Categorical features are one-hot encoded

## Model
- Algorithm: Linear Regression
- Train-Test Split: 80% / 20%
- Metrics:
  - R² Score
  - Mean Squared Error (MSE)

## How to Run

### Option 1: Google Colab
1. Open the `.ipynb` file
2. Click **Open in Colab**
3. Run all cells

### Option 2: Local
Install Dependencies:
```bash
pip install -r requirements.txt
```
Run the notebook using Jupyter or VS Code.
Make sure `weatherHistory.csv` is in the same folder.
