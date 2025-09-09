# Medical Insurance Cost Predictor Model

This repository contains a predictive model for estimating medical insurance costs using Polynomial Regression. The project is implemented entirely in Jupyter Notebook, making it easy to follow, experiment with, and adapt for your own data.

## Model Description

The model uses polynomial regression to fit the provided dataset and predict insurance costs. The features used for prediction include:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

The dataset used for training should have these columns to ensure accurate predictions.

## Features

- **Exploratory Data Analysis (EDA):** Visualize and analyze the key features that impact insurance costs.
- **Data Preprocessing:** Handle missing values, encode categorical variables, and scale numerical features for modeling.
- **Model Training:** Train and evaluate the polynomial regression model with various degrees.
- **Performance Metrics:** Assess models using metric like R² Score.
- **Prediction:** Make cost predictions for new data samples.

## Dataset

Typically, the notebook uses the popular [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) from Kaggle. Make sure to place the dataset in the project directory or update the notebook path accordingly.


## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Pip (Python Package Installer)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bedigambar/Medical-Insurance-Cost-Predictor-Model.git
   cd Medical-Insurance-Cost-Predictor-Model
   ```

2. **Install dependencies:**
   You can install the necessary libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```
   Or install manually:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook Medical_Insurance_Cost_Predictor.ipynb
   ```

## Usage

- Follow the steps in the Jupyter Notebook to load the data, run EDA, preprocess features, train model, and make predictions.
- You can modify the notebook to use your own dataset or try different model parameters.

## Results

The notebook will guide you through model evaluation and display relevant plots and metrics. You can experiment with different hyperparameters to optimize prediction accuracy.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the model, add new features, or enhance documentation.
1. Fork the repository.
2. Create a new branch ``git checkout -b feature-branch``.
3. Commit your changes ``git commit -am 'Add new feature'``.
4. Push to the branch ``git push origin feature-branch``.
5. Create a new Pull Request.

## License

This project is released under the [MIT License](LICENSE).
