# Multiple Linear Regression to Predict Price of Used-Cars

Our objective is to identiy most significant variables that impact the price of a used car. Goal is to find out

- Which variables (age,mileage,model,brand etc) are significant in predicting the price of a car?
- How well those variables describe the price of a used car?

To help us with our descriptive goals of undersanding the signifiance of features and eliminate those dont meet the level of signifiance we will be using statsmodel.api and performing

1. RFE (Recursive feature elimination)
2. VIF (Variance Influence Factor)
3. Some Feature Engineering

## Insights from the Model 

Our Model explains 88% of the Price Variability or 88% of the factors that determine the price of used cars. 
1. Engine Volume, Registration & Newer models have significant positive impact on price. 
2. Among Brands, Renault looses value the fastest followed by Mitsubishi. 
3. Among Body Types, Body type Wagon retains the value better. 
4. Petrol engine is negatively correlated with the price of used cars
