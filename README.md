# Credit_Risk_Classification

The goal of this analysis is to find a machine learning model that predicts unbalanced data for healthy and unhealthy loans. The data is inbalanced because it has more data for healthy loans compared to the unhealthy loans. Because the data is imbalanced, the model does a better job at predicting the healthy loans compared to the unhealthy loans. To achieve better results at predicting the unhealthy loans, the data was oversampled to balance the data.

---

## Machine Learning Stages

1. Decide on the machine learning model. For this analysis, we used the Logistic Regression model.

2. Split the data into training and testing sets.

3. Fit and train the model.

4. Make predictions using the trained machine learning model. 

5. Repeat the process using oversampled data to evaluate the model's performance using two different datasets. 

---

## Analysis

Two machine learning models were used to complete this analysis. The first model used the original dataset, and the second used an oversampled dataset witht he goal of improving the accuracy, precision, and recall for the unhealthy loans. 

The accuracy for the model using the original dataset was 95%. This model did a better job of predicting the healthy loans compared to the unhealthy loans because the data was imbalanced. The precision for the unhealthy loans was 85%, while the recall was 91%.

The second machine learning model used oversampled data to achieve better precision and recall for the imbalanced dataset. The accuracy for this model was 99%, with a precision of 84% and a recall of of 99%. This model does a better job at predicting the unhealthy loans. 

---

## Contributors 

Thomas Brierton and UCB

---

## License

MIT