## Dependencies
The necessary python libraries are listed in `requirements.txt` and can be installed via
```
pip install -r requirements.txt
```
The experiments were conducted in `Python 3.11`
\
\
The original data can be found at 
\
\
**heart-disease**: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction \
\
**pneumonia**: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
 ## Project Structure
The `code` folder contains two folders, one for each part of the project containing the jupyter notebooks that can be run after data has been placed in the correct folder.
\
\
We stored the data in a seperate folder called `data` which is not part of this repository/submission
\
\
The notebooks expect the following folder structure in order to run
```
├── code
│   ├── heart-disease
│   │   ├── Q1-exploratory-data-analysis.ipynb
│   │   ├── Q2-logistic-lasso-regression.ipynb
│   │   ├── Q3-multi-layer-perceptrons.ipynb
│   │   └── Q4-neural-additive-models.ipynb
│   └── pneumonia-prediction
│       └── pneumonia-prediction.ipynb
├── data
│   ├── chest_xray
│   │   ├── test
│   │   ├── train
│   │   └── val
│   └── heart_failure
│       ├── test_split.csv
│       └── train_val_split.csv
├── readme.md
└── requirements.txt
```