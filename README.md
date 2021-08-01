DATA SCIENCE CHALLENGE SCL WEEK 2
=================================

Predict Particles Velocity
==============================

# Create a predictive MACHINE LEARNING (not ANN) algorithm to predict the relative velocity of the particles. The aim is to find the algorithm that minimizes the mean squared error (MSE).  

---

## ✨ BACKGROUND ✨
NASA has designed a new type of sensor that, from measuring the electromagnetic variation in a field, it can estimate the velocity of one particle relative to the velocity of the other particle. In this challenge, the data obtained from this sensor will be used to train a predictive model to predict that relative velocity.  

---  

## ✨ DATASET ✨
For this challenge two datasets are provided, the dataset for training the predictive algorithm and the dataset for testing the predictive algorithm.

### train.csv
(6 columns x 7000 rows) the first 5 columns contains the predictive variables and the 6 column contains the target to predict.

### X_test.csv
(5 columns x 3000 rows) contains the predictive variables to test your algorithm.  

--- 

## ✨🏆 TASK 🏆✨
Create a predictive MACHINE LEARNING (not ANN) algorithm to predict the relative velocity of the particles. The aim is to find the algorithm that minimizes the mean squared error (MSE).  

---  

## ✨ DELIVERY ✨
Paste the link to your Github repository with two files, one containing all the code you have made in either '.py' or '.ipynb' format. And another file with the values predicted by your algorithm. The file with the predictions has to be a '.csv' and only has to be a column with the predictions as it appears in the example file 'example_predictions_delivery.csv'.



Project Organization
--------------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
