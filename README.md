# Movie Rating Prediction

This project trains a simple model to predict movie ratings from a labeled training set, then generates predictions for an unlabeled test set.

## Files in this repo
- `movies_training_set.csv` – Training data with movie features and known ratings.
- `movies_testing_set.csv` – Test data with movie features and no ratings.
- `movie_rating_predictions.csv` – Model predictions for the test set (created/overwritten by the notebook).
- `new_data_predictor.ipynb` – Jupyter notebook that loads the data, trains the model, and saves predictions.

## Setup
1. Install Python 3 and pip.
2. (Optional) Create and activate a virtual environment.
3. Install Jupyter:
   ```powershell
   pip install jupyter
   ```

## Run the notebook
From the project folder in Windows PowerShell:
```powershell
jupyter notebook new_data_predictor.ipynb
```
Then run the cells in order (or use "Run All") to train the model and create predictions.

## Output
Running the notebook will save predicted ratings to `movie_rating_predictions.csv` in this folder, overwriting any existing file.
