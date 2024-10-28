<h1>Customer-Churn_Analysis</h1>

This project aims to help **PowerCo**, a gas and electricity utility company, predict churn among its SME (small and medium enterprise) customers. With the liberalization of the energy market, understanding churn drivers—especially price sensitivity—has become critical to retaining customers. This project leverages data analysis and machine learning to build a predictive model for customer churn, focusing on identifying features that can drive churn-related insights.


## Project Overview

PowerCo's SME segment has been experiencing significant churn due to the power liberalization of the energy market in Europe. This project, in collaboration with BCG, seeks to develop a predictive churn model to identify churn-prone customers, providing actionable insights to retain them effectively.

### Objective:
- Diagnose the primary drivers of churn, with a focus on price sensitivity.
- Build a churn prediction model with high accuracy, identifying features that correlate with churn.

## Data and Features

The dataset includes:
1. **Customer Data**: Usage statistics, customer tenure, and forecasted usage.
2. **Pricing Data**: Fixed and variable pricing over time.
3. **Churn Indicator**: Indicates if a customer has churned or not.


## Process Workflow

### Step 1: Exploratory Data Analysis (EDA)
- Analyze data types, distributions, and correlations to understand trends.
- Visualize customer churn rates and identify significant factors influencing churn.
- Tools: **Pandas**, **Matplotlib**, **Seaborn**

### Step 2: Hypothesis Testing and Price Sensitivity Analysis
- Test if price sensitivity is significantly correlated with churn.
- Define and calculate price sensitivity using features such as pricing changes over time and customer reaction.
- Tools: **Scipy** (for statistical tests), **Numpy**

### Step 3: Feature Engineering
- Create relevant features, such as **average monthly spend**, **recent price changes**, and **tenure**.
- Encode categorical variables and scale numerical features.
- Tools: **Pandas**, **Scikit-learn**

### Step 4: Model Training and Evaluation
- Build a **Random Forest** classifier model to predict churn, fine-tune parameters, and evaluate model performance.
- Measure accuracy, recall, and other metrics to determine predictive power.
- Tools: **Scikit-learn**

### Step 5: Findings and Recommendations
- Summarize insights, including churn drivers, the impact of price sensitivity, and potential discounts to retain customers.
- Create an abstract slide or document with these insights for client review.

---


- **Programming Language**: Python
- **Key Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `numpy`: For numerical operations and calculations.
  - `matplotlib`: For creating static visualizations.
  - `seaborn`: For advanced data visualizations and statistical graphics.
  - `scikit-learn`: For implementing machine learning algorithms (if modeling is performed).

