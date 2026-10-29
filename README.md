# Heart Disease Prediction

This project explores a medical dataset to build and evaluate a predictive model for detecting whether a patient is likely to have heart disease.

## Project Goal

The aim is to use patient health indicators and medical history to predict whether heart disease is present. The project is implemented as a Jupyter notebook and uses tabular data stored in CSV files.

## Files in This Repository

- `Heart_Disease_Prediction.ipynb` — main notebook containing data loading, exploration, preprocessing, modeling, and evaluation
- `values.csv` — patient feature data used as model inputs
- `labels.csv` — target labels indicating whether heart disease is present
- `description.docx` — project description document

## Dataset

The dataset includes features such as:

- age
- sex
- chest pain type
- resting blood pressure
- serum cholesterol
- fasting blood sugar
- resting ECG results
- maximum heart rate achieved
- exercise-induced angina
- oldpeak (ST depression)
- slope of peak exercise ST segment
- number of major vessels
- thal

The target variable is a binary label indicating the presence or absence of heart disease.

## Requirements

To run the notebook, install the following Python packages:

- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn
- jupyter

Example installation:

```bash
pip install pandas numpy matplotlib scikit-learn seaborn jupyter
```

## How to Run

1. Open the project folder in your preferred Python environment.
2. Launch Jupyter Notebook or VS Code Notebook support.
3. Open `Heart_Disease_Prediction.ipynb`.
4. Run the cells in sequence.

## Workflow

The notebook typically includes:

- loading the dataset
- checking for missing values
- analyzing feature distributions
- preparing training and testing data
- training a machine learning classifier
- evaluating predictive performance
- interpreting the results

## Notes

This project is intended for educational and research use. It should not be used as a substitute for medical advice or diagnosis.

## License

This project does not currently include a formal license file. If you plan to share or reuse it publicly, add a suitable open-source license such as MIT or Apache 2.0.
