# Airbnb Price Prediction - CDMX

## Setup Instructions

### 1. Install Python
Make sure you have Python 3.8+ installed.

### 2. Install Dependencies
```bash
pip install -r requirements.txt --break-system-packages
```

### 3. Run the Analysis
Data recovered from: [Inside Airbnb](https://insideairbnb.com/get-the-data/)



### Expected Runtime
- Data loading: 10 seconds
- OLS: 5 seconds
- LASSO: 1-2 mins
- Random Forest: 1-4 mins
- GBM: 1-4 mins
- XGBoost: 2-4 mins

### Structure
```
Data-Analysis-3/
│
├── requirements.txt          
├── README.md  
├──DA3_Assignment_1.ipynb                       
│
├── raw_data/                   
│   ├── listings_cdmx_Q2.csv.gz
    ├── listings_cdmx_Q3.csv.gz
    ├── listings_San_Mateo_Q3.csv.gz
