# From Underfitting to Overfitting: A Comparative Study of Linear and Polynomial Regression Models

## Project Overview
This project demonstrates the concepts of **underfitting and overfitting** in machine learning using linear and polynomial regression models. The study explores how model complexity affects performance and highlights the importance of selecting an appropriate model to achieve good generalisation.

The analysis is conducted using real-world **CO₂ emissions per capita data** obtained from the World Bank.

---

## Dataset
- Source: World Bank  
- Indicator: CO₂ emissions (metric tons per capita)  
- Link: https://data.worldbank.org/indicator/EN.GHG.CO2.PC.CE.AR5  

The dataset represents a time series where:
- Input (X): Year  
- Output (y): CO₂ emissions per capita  

---

## Methodology
The following steps were performed:

1. Data preprocessing and cleaning  
2. Train-test split (80/20)  
3. Model implementation:
   - Linear Regression (baseline)
   - Polynomial Regression (degrees 2–12)
4. Model evaluation using RMSE  
5. Visualisation of:
   - Model fits
   - Training vs test error
   - Underfitting and overfitting behaviour
6. Regularisation using Ridge Regression  

---

## Results
Key findings include:
- Linear regression underfits the data  
- High-degree polynomial models overfit  
- Degree 3 polynomial provides optimal performance  
- Ridge regression reduces overfitting in complex models  

---

##  How to Run the Code

1. Clone the repository:
```bash
git clone https://github.com/hninhninphyu8895/FROM-UNDERFITTING-TO-OVERFITTING-A-COMPARATIVE-STUDY-OF-LINEAR-AND-POLYNOMIAL-REGRESSION-MODELS-.git
