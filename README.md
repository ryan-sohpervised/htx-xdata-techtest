# HDB Resale Price Prediction

A machine learning project to predict HDB (Housing and Development Board) resale flat prices in Singapore using historical transaction data and advanced modeling techniques.

## Installation

### Prerequisites
- Python 3.12 or higher
- pip (Python package manager)

### Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd htx-xdata-techtest
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

This will install all required packages including:
- Data processing: `pandas`, `numpy`
- Machine learning: `scikit-learn`, `xgboost`
- Deep learning: `torch`, `torch-geometric`
- Hyperparameter optimization: `optuna`
- Model interpretation: `shap`
- Visualization: `matplotlib`, `seaborn`, `plotly`

3. Launch the Jupyter notebook:
```bash
jupyter notebook model_prediction_task/model_prediction_task.ipynb
```

## Project Structure

```
├── data/
│   └── HDB/                    # Historical HDB resale price data
├── model_prediction_task/
│   └── model_prediction_task.ipynb    # Main analysis and modeling notebook
├── requirements.txt            # Python dependencies
└── README.md                   # This file
```

## Quick Start

Open the Jupyter notebook `model_prediction_task/model_prediction_task.ipynb` and run the cells to:
- Load and explore the HDB resale data
- Perform data preprocessing and feature engineering
- Train and evaluate prediction models
- Visualize results and model performance
