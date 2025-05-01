# Titanic Survival Prediction

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/640px-RMS_Titanic_3.jpg)

## Project Overview
This project focuses on predicting passenger survival from the tragic Titanic disaster using machine learning techniques. The sinking of the RMS Titanic is one of the most infamous shipwrecks in history, occurring on April 15, 1912, during her maiden voyage.

### Dataset
The dataset contains demographics and passenger information from 891 of the 2224 passengers and crew on board. The data includes:
- Passenger information (Age, Sex, Class, etc.)
- Cabin information
- Ticket information
- Survival status (target variable)

## Project Structure
```
.
├── data/
│   ├── train.csv
│   └── test.csv
├── models/
│   └── model.ipynb
├── README.md
└── requirements.txt
```

## Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - Xgboost

Install the required packages:
```
pip install -r requirements.txt
```

## Data Preprocessing
The preprocessing steps include:
- Handling missing values
- Feature engineering
- Encoding categorical variables
- Feature scaling

## Models
Multiple classification algorithms were tested:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine
- Gaussian Naive Bayes

## Performance Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Key Insights
1. **Gender**: Being female was a significant survival advantage
2. **Class**: First-class passengers had higher survival rates
3. **Age**: Children were prioritized for rescue
4. **Family**: Passengers traveling with family had different survival patterns than those traveling alone

## Results
The best-performing model achieved an accuracy of 82.3% on the validation set, with a cross-validation score of 80.9%.

## How to Use
1. Clone the repository
```
git clone https://github.com/Twahaaa/Titanic-Classification.git
cd Titanic-Classification
```

2. Install requirements
```
pip install -r requirements.txt
```

3. Run exploratory data analysis
```
jupyter notebook notebooks/exploratory_data_analysis.ipynb
```

4. Train and evaluate models
```
jupyter notebook notebooks/model_development.ipynb
```



## Acknowledgements
- [Kaggle](https://www.kaggle.com/competitions/titanic) for providing the dataset
- [Reference](https://youtu.be/6IGx7ZZdS74?si=cjHi_ueqNHSvqzOa) for the tutorial on how to do this
