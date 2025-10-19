# House Price Predictor

A machine learning model that predicts house prices based on size, number of bedrooms, and age of the property.

## 🚀 Features

- **Accurate Predictions**: Achieves 94.5% R² score with only 4% average error
- **Easy to Use**: Simple interface for price predictions
- **Scalable**: Built with scikit-learn pipeline for easy deployment

## 📊 Model Performance

- **R² Score**: 0.945 (94.5% variance explained)
- **RMSE**: ~$15,109 average error
- **Mean Error**: 4% of house price

## 🛠️ Tech Stack

- Python 3.8+
- scikit-learn
- pandas
- numpy

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/house-price-predictor.git
cd house-price-predictor
```

2. Install dependecies
```bash
pip install -r requirements.txt
```

3. Run the prediction
```bash
python house_price_predict.py
```

## 📖 Usage

1. Run the prediction script:
```bash
python house_price_predict.py
```

2. Enter house details when prompted:
- House size in square feet
- Number of bedrooms
- Age of the house in years

3. Get instant price prediction

## 🏗️ Project Structure
```text
├── model.py                    # Model training and pipeline
├── house_price_predict.py      # Prediction interface
├── house_price_prediction_data.csv  # Training dataset
├── README.md
└── requirements.txt
```

## 📈 Model Details
- Algorithm: Linear Regression with StandardScaler
- Features: Size, Bedrooms, Age
- Target: House Price
- Training Data: 200 realistic house listings
