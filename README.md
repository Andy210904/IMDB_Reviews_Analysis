## IMDB Movie Rating Prediction

## Objective
This project aims to build a machine learning model that predicts movie ratings based on various attributes such as genre, director, main actor, and more. The project is developed entirely using **Google Colab**, with data and models.

---

## ⚙️ How to Run (in Google Colab)

1. Open the `Movie_Rating_Prediction.ipynb` file on Google Collab.
2. Upload the IMDB dataset on the files section in Google Collab
3. Run all the cells sequentially.

Dependencies such as `pandas`, `scikit-learn`, `seaborn`, and `joblib` will be auto-installed within the notebook.

---

## 🧠 Features Used

- **Categorical Encoding**: Genre, director, and actor labels encoded with `LabelEncoder`.
- **Director Success Rate**: Average rating of movies previously directed.
- **Genre Average Rating**: Mean rating of all movies in the same genre.
- **Other Features**: Budget, revenue, and release year can also be added based on availability.

---

## 📊 Model & Evaluation

- **Model**: Random Forest Regressor (Scikit-learn)
- **Metrics**:
  - Root Mean Squared Error (RMSE)
  - R² Score
- **Visualizations**:
  - Actual vs Predicted Rating Scatterplot
- **Cross-validation** may be added for enhanced performance tuning.


## 💾 Output Files

- `models/rating_model.pkl`: Trained model for future inference.
- `outputs/metrics.txt`: RMSE and R² Score of the model.
- `outputs/actual_vs_predicted.png`: Evaluation visualization plot.

---

## ✅ Expected Outcome
A regression model capable of accurately predicting movie ratings based on user-defined inputs and historical movie data.

