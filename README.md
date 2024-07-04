# Airline Passenger Satisfaction Project

## Introduction

This project is a final assignment for the Neural Networks course at the Informatics Center of the Federal University of Pernambuco, taught by Professor Germano Vasconcelos. The aim is to analyze and predict airline passenger satisfaction using various neural network models.

## Dataset

The dataset used in this project is sourced from Kaggle: [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data). It contains a variety of features related to passenger demographics, flight details, and service ratings. The key features include:

## Project Goals

The primary objectives of this project are:

1. **Data Exploration and Preprocessing**: Understand the structure of the dataset, handle missing values, and preprocess the data for modeling.
2. **Feature Engineering**: Create new features that could help in improving model performance.
3. **Model Building**: Develop various neural network models to predict passenger satisfaction.
4. **Model Evaluation**: Evaluate the performance of the models using appropriate metrics and choose the best-performing model.

## Requirements

To replicate this project, you need the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow`
- `pytorch`
- `plotly`
- `pykan`
- `scipy`

You can install these libraries using pip:

```bash
pip install -r requirements.txt
```

## Project Structure

The project repository is organized as follows:

```
├── notebooks
│   ├── eda_and_data_processing.ipynb
│   ├── mlp_model.ipynb
│   ├── rf_model.ipynb
│   ├── xgb_model.ipynb
│   └── kan_model.ipynb
├── README.md
└── requirements.txt
```

## Usage

1. **Clone the repository**:

```bash
git clone https://github.com/w-alves/airline-passenger-satisfaction.git
cd airline-passenger-satisfaction
```

2. **Install the required libraries**:

```bash
pip install -r requirements.txt
```

3. **Run the notebooks** in sequence to perform data exploration, preprocessing, feature engineering, model building, and evaluation.

## Conclusion

This project showcases the application of neural networks in predicting airline passenger satisfaction. It provides a comprehensive workflow from data exploration to model evaluation, offering valuable insights into factors influencing passenger satisfaction.

Feel free to explore the code, run the notebooks, and experiment with different neural network architectures and hyperparameters. If you have any questions or suggestions, please feel free to reach out.

---

**Authors**: Wesley Alves, Weybson Alves, Lucas Leonardo  
**Course**: Neural Networks  
**Institution**: Informatics Center, Federal University of Pernambuco  
**Professor**: Germano Vasconcelos
