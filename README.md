# Data Science Case Study

The purpose of this assessment is to understand how you approach analysis and the application of data science to a business problem.

You must use Python to complete this assessment. You may also use SQL for performing queries and data modelling


## Poetry

To load the Poetry environment and run the code:

### Install dependencies
```bash
poetry install
```

### Activate the virtual environment
```bash
poetry shell
```

### Run your analysis scripts or notebooks
```bash
python your_script.py
```

***If using a notebook makre sure you set the kernal to the poetry env you have created***

### Find you poetry env
```bash
poetry env list
```


## 1. Problem Statement

You are a Data Scientist at a leading UK travel company. The business wants to grow ticket sales across its network of train stations, but marketing and infrastructure budgets are limited. Leadership needs to know where to invest to maximise returns — whether that’s through marketing campaigns, station improvements, or better allocation of existing resources.

To support this, you are given two datasets:
- station_sales.csv – daily ticket sales data for a selection of UK stations (simulated, with realistic seasonal patterns).
- station_location.csv – information on station location, and operator.

## 2. The Ask:

### Q1: Understanding the Market
- How has sales growth trended across stations and regions over time?
- Are there certain stations or regions that stand out — either as growth leaders or as underperformers?
- What are the key seasonal patterns (weekly and annual)?
- Based on this, can you build a baseline forecast for the next 12 months? (You can choose any methodology — statistical or ML — but be ready to explain your choice.)

### Q2: Exploring Data Science Use Cases
Looking beyond descriptive analysis and forecasting, what machine learning use cases could be tested on this data?
Select a use case and prototype a model to demonstrate the application of data science to solving their problem. You could explore looking at adding external information if you may please, but you won’t be strictly evaluated on it. You are not evaluated on the accuracy or performance of the model, but more so on your approach.

### Q3: Recommendations for the Business
Based on our analysis, what key insights should the business act on and why? What other data would you use to help support your case if available.
