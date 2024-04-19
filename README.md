# SC1015 Data Science Project - **Suicide Rates**
----------------
## About
Our team's objective is to reduce the number of suicide rates by understanding what factor(s) contribute to the large number of suicide rate from [Dataset]( https://www.kaggle.com/datasets/ronaldonyango/global-suicide-rates-1990-to-2022).
![FCE 3, Team 2 (1)](https://github.com/UsamaBafana/SC1015/assets/63994902/8ca7f055-36c0-4021-9da0-91032c290ed6)

For detailed 

-----
## Contributors 
1. Jun Hao -
2. Karthik -
3. Usama -

-----
## Problem Definition
> [!IMPORTANT]
>  What **socioeconomic factors** might be behind the suicide rates in the world?


> [!IMPORTANT]
> Which model is best used to predict death rate?
----
## 5 Models were used:
1. Linear Regression
2. Decision tree Regression
3. Polynomial Regression
4. Random Forest Regression
5. Gradient Boosting Regression
-----
## Conclusion
By the results of the 5 models that were used, we decided that 3 models could be used;
>Polynomial Regression (best)
>
>Decision Tree (2nd best)
>
>Linear Regression (3rd best)

The other 2 models that we attempted to use performed much worse compared to Linear Regression and Polynomial Regression
- Random Forest Regression by far produced the worst R^2 and MSE output
- Gradient Boosting was bad but not as bad as random forest

Polynomial Regression > Decision Tree > Linear Regression  >Gradient Boosting > Random Forest

### Final Insights
1. Male suicide rates are *higher* than females.
2. Selected `GNIPerCapita` as our predictor variable 
3. Some region have not enough data points to do machine learning, therefore we have chosen data from `Europe` and `Asia`
4. Concluded to disregard female data as there is *no correlation* of StdDeathRate with GNIPerCapita.

