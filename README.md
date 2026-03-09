# Laptop-Price-Prediction-Using-ML-Final-Model

## Project Overview
This project aims to predict laptop prices based on product specifications such as CPU type, RAM, storage capacity, GPU, screen size, and brand. We compare traditional machine learning algorithms with an Artificial Neural Network (ANN) to determine the best-performing model for continuous price estimation (in Euros).

## Repository Structure
* `/data`: Contains the `laptop_price - dataset.csv` file.
* `/notebooks`: Contains the primary Jupyter Notebook (`Nonames_Project.ipynb`) featuring the data pipeline, Exploratory Data Analysis (EDA), and model training.
* `/src`: Contains any supplementary Python scripts for preprocessing or custom functions.
* `/results`: Stores output plots, model evaluation metric tables, and the final project report.
* `README.md`: Project overview and execution instructions.
* `requirements.txt`: List of required Python dependencies.

## Dataset
* **Source**: Kaggle (Laptop Price Dataset).
* **Size**: 1,275 rows and 15 columns.
* **Features**: Includes numerical attributes (e.g., RAM, storage, screen size) and categorical attributes (e.g., brand, CPU type, GPU).
* **Target Variable**: Price (Euro).

## Requirements
To run this project, you will need Python 3.x and the following libraries:
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

## How to run (brief):

1. This project builds a machine learning model to predict laptop prices based on hardware specifications. First, necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are imported, and the dataset is loaded for analysis.
2. The dataset is explored by checking its structure, statistical summary, and missing values. The data is then divided into features (X) and the target variable (Price), followed by splitting it into training and testing sets.
3. Next, preprocessing is applied where numerical features are scaled and missing values are handled, while categorical features are converted into numerical format using One-Hot Encoding. Additional feature engineering is performed to extract useful attributes such as Touchscreen, IPS display, PPI, and different storage types.
4. Several machine learning models including Linear Regression, Decision Tree, Random Forest, KNN, and Artificial Neural Network (MLP) are trained and evaluated. Their performance is measured using MAE, RMSE, and R² score.
5. Finally, the results are presented in tables and visualized using graphs to compare the performance of the models and analyze feature correlations with laptop price.

## Dataset link/location: 
https://www.kaggle.com/datasets/ironwolf437/laptop-price-dataset
