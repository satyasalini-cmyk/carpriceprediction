# Car Price Prediction - Linear Regression ML Project

A machine learning project that predicts car prices using linear regression analysis.

## Overview

This project demonstrates a complete machine learning workflow for predicting car values using various car features such as horsepower, torque, make, body style, and other specifications.

## Features

- **Data Preprocessing**: Cleaning, handling missing values, and feature engineering
- **Exploratory Data Analysis**: Comprehensive data visualization and analysis
- **Machine Learning**: Linear regression model implementation
- **Model Evaluation**: Performance metrics including R², RMSE, and MAE
- **Feature importance**: Analysis of which features most impact car prices
- **Streamlit App**: Interactive web application for predictions

## Project Structure

```
├── Linear Regression ML.ipynb    # Main Jupyter notebook with complete analysis
├── Regr_model_cars.py           # Streamlit application
├── car_data.csv                 # Dataset
├── linear_model.pkl             # Trained model
├── feature_importance.xlsx      # Feature importance results
├── requirements.txt             # Python dependencies
├── imgs/                        # Images and visualizations
└── README.md                    # Project documentation
```

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd linearregression
```

2. Create a virtual environment:
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1  # On Windows PowerShell
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Jupyter Notebook
Open `Linear Regression ML.ipynb` in Jupyter or VS Code to see the complete analysis.

### Running the Streamlit App
```bash
streamlit run Regr_model_cars.py
```

## Machine Learning Process

1. **Problem Formulation**: Predict car prices based on vehicle specifications
2. **Data Loading**: Import and examine the car dataset
3. **Data Preprocessing**: 
   - Handle missing values
   - Feature engineering (extracting numeric values from text)
   - Data type conversions
4. **Exploratory Data Analysis**:
   - Statistical analysis
   - Correlation analysis
   - Data visualization
5. **Model Training**: Linear regression implementation
6. **Model Evaluation**: Performance assessment using multiple metrics
7. **Feature Importance**: Identifying key price predictors
8. **Model Persistence**: Saving trained model for deployment

## Key Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- plotly
- streamlit
- openpyxl

## Results

The model achieves good performance in predicting car prices with detailed evaluation metrics available in the notebook.

## Contributing

Feel free to fork this project and submit pull requests for improvements.

## License

This project is open source and available under the MIT License.
