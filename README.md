## IMDB Movie Rating Prediction

## Objective
This project aims to build a machine learning model that predicts movie ratings based on various attributes such as genre, director, main actor, and more. The project is developed entirely using **Google Colab**, with data and models.

---

## How to Run (in Google Colab)

1. Open the `Movie_Rating_Prediction.ipynb` file on Google Collab.
2. Upload the IMDB dataset on the files section in Google Collab
3. Run all the cells sequentially.

Dependencies such as `pandas`, `scikit-learn`, `seaborn`, will be auto-installed within the notebook.

---

## Features Used

- **Categorical Encoding**: Genre, director, and actor labels encoded with `LabelEncoder`.
- **Director Success Rate**: Average rating of movies previously directed.
- **Genre Average Rating**: Mean rating of all movies in the same genre.

---

## Model & Evaluation

- **Model**: Random Forest Regressor (Scikit-learn)
- **Metrics**:
  - Root Mean Squared Error (RMSE)
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
- **Visulization**:
  - Scatter Plot for actual ratings vs predicted ratings

## Test Data also added to check for new values
- Visualization for test cases with predicted vs actual ratings
---

