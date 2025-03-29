# Heart Disease Prediction using Logistic Regression

## Overview
This project focuses on predicting heart disease using a logistic regression model. The model is trained on the real-life **Framingham Heart Study dataset**, which contains over 4,000 records with 15 attributes. The performance of the model is evaluated using accuracy, precision, recall, and F1-score.

## Dataset
- **Name**: Framingham Heart Study Dataset
- **Size**: 4,000+ records
- **Attributes**: 15 features including age, sex, cholesterol levels, smoking status, diabetes, blood pressure, etc.
- **Target Variable**: Presence or absence of heart disease

## Model & Methodology
- **Algorithm**: Logistic Regression
- **Libraries Used**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Preprocessing Steps**:
  - Handling missing values
  - Feature selection
  - Data normalization
  - Splitting dataset into training and testing sets (e.g., 80-20 split)

## Evaluation Metrics
- **Accuracy**: Measures overall correctness of predictions.
- **Precision**: Evaluates how many positive predictions were actually correct.
- **Recall (Sensitivity)**: Measures the model’s ability to detect actual positive cases.
- **F1-score**: Harmonic mean of precision and recall, balancing both.

## Installation & Usage
### Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Running the Model
1. Clone the repository:
   ```bash
   git clone https://github.com/nandnir204/HeartDiseasePrediction.git
   cd heart-disease-prediction
   ```
2. Run the script:
   ```bash
   python heartdiseaseprediction-logisticregression.py
   ```
3. View model performance metrics in the console or saved output file.

## Results & Conclusion
The model's performance is evaluated based on the mentioned metrics. Future improvements may include feature engineering, hyperparameter tuning, or testing other machine learning models such as Decision Trees or Neural Networks.

## Contact
For any queries, reach out to [Nandini Rajoria] at nandinirajoria204@gmail.com.

