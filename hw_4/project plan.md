## Data Set Information:
The dataset are related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).
The classes are ordered and not balanced (e.g. there are munch more normal wines than excellent or poor ones).

## Attribute Information:
##### Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
##### Output variable (based on sensory data):
12 - quality (score between 0 and 10)

## Feature Engineering
Added two variables.
One shows whether the wine is low alcohol (alcohol < 10), the second whether the wine is highly alcoholic (alcohol > 12).

## Model
We have used standard Logistic Regression with default parameters.




