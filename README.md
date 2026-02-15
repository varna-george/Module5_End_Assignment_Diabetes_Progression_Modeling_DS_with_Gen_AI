Module 5 End Assignment - Diabetes Progression Modeling

Objective: To model the progression of diabetes using the available independent
variables. This model will help healthcare professionals understand how different factors influence the progression of diabetes and potentially aid in designing better treatment plans and preventive measures. The model will provide insights into the dynamics of diabetes progression in patients.

Dataset: Diabetes dataset available in the sklearn library.

Key components to be fulfilled:
1. Loaded the dataset, No missing values found, Features are normalized using StandardScaler to ensure all inputs are on a similar scale.
2. Exploratory Data Analysis (EDA)
3. Building the ANN Model
4. Training the ANN Model
5. Evaluating the Model: The baseline ANN shows moderate performance with an R² score of 0.16, indicating partial learning of diabetes progression patterns and scope for further optimization.
6. Improving the Model - 
Model Enhancements: To improve the performance of the baseline ANN model, the following changes were made:

(i) Increased the number of neurons in the hidden layer to help the model learn more complex patterns

(ii) Added an extra hidden layer to better capture non-linear relationships in the data

(iii) Adjusted the learning rate to ensure more stable and efficient training

(iv) Increased the number of training epochs so the model could learn the data more thoroughly

Conclusion: The improved ANN model (R² score of 0.48) performs better than the baseline ANN, as it has a lower Mean Squared Error and a higher R² score. This indicates that the improved model predicts diabetes progression more accurately and explains more variation in the data.



