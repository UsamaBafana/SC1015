# SC1015 Data Science Project - **Suicide Rates**
----------------
## About
Our team's objective is to reduce the number of suicide rates by understanding what factor(s) contribute to the large number of suicide rate from [Dataset]( https://www.kaggle.com/datasets/ronaldonyango/global-suicide-rates-1990-to-2022).
![FCE 3, Team 2 (1)](https://github.com/UsamaBafana/SC1015/assets/63994902/8ca7f055-36c0-4021-9da0-91032c290ed6)

Presentation: https://www.youtube.com/watch?v=q2CZYm96TME

-----
## Contributors 
1. @Jyhrie - Jun Hao
2. @KarthikRaj2715 - Karthik
3. @UsamaBafana - Usama

-----
## Problem Definition
> [!IMPORTANT]
>  What **socioeconomic factors** might be behind the suicide rates in the world?


> [!IMPORTANT]
> Which model is best used to predict the death rate?
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

### What did we learn from the project?
#### Peak and  Fluctuation in global suicide rates:
1. Global Suicide rates have shown fluctuation over the years, peaking around 1997, decreasing subsequently, and then peaking again in 2021. This peak serves as a significant point of interest for further investigation into the societal, economic, and psychological factors that may have contributed to it.

#### Consistent Gender-Specific Trends:
1. Despite the stability in global suicide rates, the trend in suicide rates between genders has remained consistent over the years.
2. Recognizing the distinct factors including male and female suicide rates is essential.
   
#### Socioeconomic Factors:
##### Regional Variations in Suicide Trends:
1. Regional Variations suggest that socioeconomic factors, access to mental health services, and other variables may play a significant role in shaping these trends.
2. By incorporating regional data into predictive models, we can develop more accurate and robust algorithms for forecasting suicide rates. These models can help identify high-risk areas and target intervention more effectively, leading to more targeted and efficient allocation of resources for suicide prevention efforts.

##### Economic Prosperity and Suicide Rates:
1. Our analysis revealed a strong correlation between economic prosperity, Gross National Income (GNI), and suicide rates.
2. We found that as GNIPerCapita increases, the variance of suicide rates decreases, indicating a more predictive model.
3. Moreover, our analysis showed that suicide rates tend to decrease as GNIPerCapita increases.


## Conclusion
1. Gender is a major factor when trying to build a model to predict the suicide rate of a country.
2. We found that while there is a correlation between economic prosperity and suicide rates, regional variations suggest that other factors such as sociocultural influence and access to mental health services, also play a big part in shaping these trends.
3. Specifically, indicators such as GNIPerCapita and GDPPerCapita showed a significant correlation with male suicide rates. However, the correlation between socioeconomic factors and female suicide rates was less pronounced, indicating the need for further investigation.
4. Based on the findings, we can suggest that suicide rates become more unpredictable  
