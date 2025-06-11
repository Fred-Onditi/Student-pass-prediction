# Student Pass/Fail Prediction (Machine Learning Project)

This project uses machine learning to predict whether a student will pass or fail based on their demographics and academic behavior.

---

## Project Structure

```
student-pass-prediction/
├── data/                  # Contains the dataset
├── notebooks/             # Jupyter notebooks for each step
├── models/                # Saved models and preprocessing tools
├── requirements.txt       # Python libraries needed
├── README.md              # Project overview and instructions
└── .gitignore             # Files/folders Git should ignore
```

---

## Models Used

- Logistic Regression
- Random Forest (final chosen model)

---

## Evaluation Metrics

- Accuracy
- F1 Score
- Confusion Matrix

Random Forest performed best, so it's used for final predictions.

---

## How to Use the Model

1. Clone the repository or download the code.
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebooks in order:
   - 01_eda_preprocessing.ipynb
   - 02_model_training.ipynb
   - 03_prediction.ipynb
4. Add new student data to make predictions with the trained model.

---

## Author

Created by Fredrick
