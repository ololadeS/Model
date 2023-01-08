# Airline Customer Satisfaction Modeling 
The purpose of this analysis is to understand the factors that influence customer satisfaction with the airlines services and to build a predictive model that can be used to forecast satisfaction levels.

### Data:
The data was derived from Kaggle website. The data included over 120 thousands customers with various aspect of airline services. The target variable for this analysis is customer satisfaction, which is binary either (satisfied or disatisfied).

### Process 
- Perform data cleaning in preparation for analysis and spliting data into training and testing set (80, 20)
    ![image](https://user-images.githubusercontent.com/100509275/211209150-1f19b363-16a1-4f73-9eff-c867aaa9326e.png)

- Model Development:  Two predictive modes were developed for the analysis (logistic regression and Random Forest) to predict customer satisfaction based on the following predictors variables;

    ![image](https://user-images.githubusercontent.com/100509275/211209049-dda0bf70-6ad6-4bef-9b1d-53dcddc21480.png)
and the models were fit to the tranning data and tested on the test data.

- Model evaluation: The accuracy score for each models are shown below 

| Model | Score   | 
| :-----: | :---: | 
| Logistic reg | 0.84 | 
| Random Forest | 0.96 | 


### Conclusion 
Both the Logistic regression and Random Forest models were able to accurately predict customer statisfaction with airline services but the random forest had a better performance 
