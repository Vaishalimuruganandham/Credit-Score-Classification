# Capstone Project - Classification Model

## Overview
This project involves building a classification model using machine learning techniques. The dataset consists of 28 columns and 100,000 rows, with both numerical and categorical variables. The goal is to clean the data, explore patterns, and train classification models to achieve high accuracy.

## Dataset
- **Columns:** 28 (including categorical and numerical features)
- **Rows:** 100,000
- **Contains missing values:** Yes
- **Contains duplicates:** No

## Project Structure
```
|-- data/               # Raw and processed datasets
|-- notebooks/          # Jupyter Notebooks for analysis
|-- src/               # Scripts for data processing and modeling
|-- models/            # Saved trained models
|-- README.md          # Project documentation
```

## Dependencies
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- scipy

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/capstone-project.git
   cd capstone-project
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Execute the notebook `Capstone Project Final.ipynb` step by step.

## Key Steps in Notebook
1. **Data Loading**: Load and inspect the dataset.
2. **Data Cleaning**: Handle missing values and categorical encoding.
3. **Exploratory Data Analysis (EDA)**: Identify patterns and distributions.
4. **Feature Engineering**: Transform data for better model performance.
5. **Model Training**: Train various classification models (Decision Tree, Random Forest, Naïve Bayes, Logistic Regression, KNN).
6. **Model Evaluation**: Compare model performances using cross-validation.
7. **Prediction**: Use the best-performing model for final classification.

## Results
- Successfully classified data with high accuracy.
- Compared multiple models for optimal performance.

## Future Enhancements
- Tune hyperparameters to improve accuracy.
- Try deep learning models for better generalization.
- Deploy the model as an API for real-time classification.

## Author
Vaishali

## License
This project is licensed under the MIT License.

