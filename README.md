 # Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

## Introduction
Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of evaluating soil condition. However, it can also be a costly and time-consuming process, which results in farmers prioritizing which metrics to measure based on their financial constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their key objective is to boost productivity of their crops, taking into consideration different factors. One crucial factor that determines crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for her field. They have provided you with a data set called `soil_measures.csv`, which contains:
- "N": Nitrogen content ratio in the soil
- "P": Phosphorous content ratio in the soil
- "K": Potassium content ratio in the soil
- "pH": value of the soil
- "crop": categorical value that contains various crops (target variable).

Each row in this data set represent various measure of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.

## Dependencies
- matplotlib
- pandas
- sklearn

## Results
The model achieved an F1-score of 0.91 on the test set. This means that the model is able to predict correct the type of crop with 91% accuracy.

The following features were used to train the model:
- Nitrogen content ratio in the soil (N)
- Potassium content ratio in the soil (K)
- pH value of the soil (ph)

The model was able to avoid multicollinearity by selecting features that were not highly correlated.

## Conclusion
In this project, a machine learning model was built to predict the type of crop that farmers should plant based on the soil conditions in their field. The model achieved an F1-score of 0.91 on the test set, which indicates that it is able to correctly predict the type of crop with 91% accuracy. The model was able to avoid multicollinearity by selecting features that were not highly correlated.

This model can be used by all farmers to make more informed decisions about which crop to plant. By selecting the right crops for their soil conditions, farmers can maximize their crop yields and improve their profitability.
