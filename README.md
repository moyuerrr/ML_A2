# Machine Learning COMP30027 Assignment 2 Readme
In this project, we trained `CNN`, `neural-network`, `Random Forest` and `stacked model` to predict the type of traffic sign in german.

### File Structure
**ML_A2**
├── **Code**   `contains all of our works`
│   ├── **2025_A2**  `Put Train & Test Data in this dir`
│   │   ├── test
│   │   │   └── Features
│   │   └── train
│   │       └── Features
│   ├── CNN_Implementation
│   ├── **models**  `Trained model will be stored here`
│   ├── Neural_Networks
│   ├── RandomForest_Implementation
│   └── Stacking_model
└── report_template_word

### How to setup & Run
1. To run this project, you will need to install:
`scikit-learn==1.5.2
seaborn==0.13.2
matplotlib==3.10.3
tensorflow==2.19.0
numpy==2.1.3
pandas==2.2.3
keras==3.10.0
scikeras==0.13.0`
as dependencies first, with python version `3.12.2`

2. Unzip train & test data to `/Code/2025_A2` folder

3. Go to any of the `CNN_Implementation`, `Neural_Networks`, `RandomForest_Implementation` or `Stacking_model` folder to run desired model, all code are written in **Jupyter Notebook**.

4. Model predict result will present as `.csv` in the root dir of this repo.

This group project contains member: `Peihong Li` and `Suyu Chen`.