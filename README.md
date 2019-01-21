# Rain Prediction in Australia
Attempting to build a machine learning model(s) to predict whether it will rain the next day in Australia. The [dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) used in this project has approx 140k rows and 24 features. 

# Before you get started
- Good understanding of pandas library
- Intermediate understanding of sklearn library (random forest classifier, gridsearchCV, train test split)
- Basic usage of jupyter notebooks

# Setup
**How to obtain this repository:**
```sh
git clone https://github.com/danielc92/rain_prediction.git
```
**Modules/dependencies:**
- `pandas`
- `jupyter`
- `sklearn`

Install the following dependences:
```sh
cd /local/location/of/this/repo
pip install pandas jupyter sklearn
```

# Tests
- Feature engineering on source dataset
- Built model with/without `pandas.get_dummies` process

# Contributors
- Daniel Corcoran

# Sources
- [Dataset from `kaggle`](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- [Random Forest Classifier from `sklearn`](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)