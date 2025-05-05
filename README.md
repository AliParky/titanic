# titanic

This repository contains an analysis of the Titanic dataset. The goal is to build predictive models to determine the survival of passengers.

## Dataset

The dataset used in this analysis is the famous Titanic dataset from Kaggle, which contains information about passengers aboard the RMS Titanic, including:
- Demographic information
- Journey information
- Family relationships
- Survival status (target variable)

## Requirements

The following Python libraries are required to run the analysis:
- pandas
- seaborn
- matplotlib
- scikit-learn
- joblib

## Installation
To set up and run the analysis on your local machine, follow these steps:

1. First, clone the repository to your local machine.
```bash
git clone https://github.com/AliParky/titanic
```
2. Change your current working directory to the project directory.
```bash
cd titanic
```
3. Install the required libraries.
```bash
pip install requirements.txt
```
5. Run the Jupyter Notebook
```bash
jupyter notebook titanic_analysis.ipynb
```

## Usage
Open the Jupyter Notebook and run the cells in sequence to perform the analysis. Follow the instructions provided in the notebook to understand each step of the process. 

## Project Structure
- `titanic_analysis.ipynb`: The main Jupyter Notebook containing the analysis.
- `train.csv`: Training dataset used for model development and evaluation
- `test.csv`: The training dataset.
- `titanic_model.pkl`: Saved Random Forest model.