# HDB Resale Price Prediction

A machine learning project analyzing HDB (Housing and Development Board) resale data in Singapore, including price prediction modeling and link analysis of transactions. A neural network for price prediction is also trained on the graph.

## Installation

### Prerequisites
- Python 3.12
- pip

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

## Project Structure

```
├── data/
│   └── HDB/                    # Historical HDB resale price data
│       └── separate/           # folder for the 5 data files
├── model_prediction_task/
│   └── model_prediction_task.ipynb    # Price prediction modeling
├── link_analysis_task/
│   └── link_analysis.ipynb     # Link analysis of transactions
├── requirements.txt            # Python dependencies
└── README.md                   # This file
```

## Quick Start

The project includes two main tasks:

1. **Model Prediction** - Open `model_prediction_task/model_prediction_task.ipynb` to train and evaluate price prediction models
2. **Link Analysis** - Open `link_analysis_task/link_analysis.ipynb` to analyze transaction patterns and relationships

IMPORTANT NOTE: The original data files need to be loaded into 'data/HDB/separate'. 
The model prediction notebook has to be run before the link analysis notebook as the former generates the data file for the latter.
