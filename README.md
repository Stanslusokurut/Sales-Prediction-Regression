# Sales-Prediction-Regression
## Business Problem
The Project sought to predict sales of a client based on business data available using data science and  machine learnig  Techniques.

## Data and Data Sources
Business data as available for both categorical and continous variables. Data available include 
* Item weight
* Item Type
* Outlet Size
* Item Outlet sales 
* Outlet type
* Establishment year
* Fat content of the items  and other location and product identifiers 

**The dataset had 8,532 variables (rows) and 9 columns**

**Data was analysed using Hot Encoder, missing values were imputed and was test split using random = 42 and two models were fitted to it to predict sales**
* Simple Regression 
* Regression Decsion Treea

##Some Key Results
**Sales by Outlet**
![Sales by Outlet](https://user-images.githubusercontent.com/99395688/226849271-e274dc01-e405-4a1c-8059-c5266fde8d31.png)


**Errors of the Simple regression plotted by Indeex
![Errors of Predicted Variables](https://user-images.githubusercontent.com/99395688/226849309-7a23902c-f329-429d-ab2e-39cdfd4e436f.png)

**KEY FINDINGS**
* 1. The Simple regression model predcited sales better than the decsion tree based on R2 values and MSE values
* 2. The business should adopt te simple regression as the model to predict sales 
