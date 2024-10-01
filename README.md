# **Insurance Premium Prediction**

This project aims to predict the insurance premium cost for individuals based on personal details such as age, BMI, smoking status, and region. The model is built using the **Random Forest Regressor** algorithm in Python, leveraging various libraries for data processing and modeling.

## **Overview**
The objective of this project is to predict the medical insurance premiums that an individual would need to pay based on factors such as age, BMI, number of children, and smoking habits. The **Random Forest Regressor** algorithm was chosen for its efficiency and ability to handle complex, non-linear relationships in the dataset.

## **Dataset**
The dataset consists of the following features:

- **age**: Age of the individual.
- **sex**: Gender of the individual (male/female).
- **bmi**: Body Mass Index (BMI) of the individual.
- **children**: Number of children/dependents.
- **smoker**: Smoking status (yes/no).
- **region**: The region where the individual lives (northwest, southwest, etc.).
- **premium**: The insurance premium (target variable).

## **Tools and Libraries**
This project was implemented using Python, with the following libraries:
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Scikit-learn**: Machine learning algorithms and model evaluation.
- **Matplotlib/Seaborn**: Data visualization.

## **Methodology**
1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables such as `sex`, `smoker`, and `region`.
   - Scaling the numerical features like `age` and `bmi` to improve model performance.

2. **Model Selection**:
   - A **Random Forest Regressor** was chosen for its ability to capture non-linear relationships and handle large amounts of data with high accuracy.

3. **Model Evaluation**:
   - The model was evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)** score to assess the performance of the predictions.

## **Modeling**
The **Random Forest Regressor** algorithm was applied to the preprocessed dataset. The model was trained using 80% of the data, and the remaining 20% was used for testing. Hyperparameter tuning was performed to enhance the performance of the model by adjusting the number of trees, depth, and other parameters.

## **Conclusion and Solution**
The **Random Forest Regressor** performed well in predicting the insurance premium costs. The model showed that **BMI**, **age**, and **smoking status** are the most influential factors in determining the premium cost. 

This model can assist insurance companies in automating and personalizing insurance premium calculations, helping to streamline the process while maintaining accuracy. Future work could include expanding the dataset and incorporating additional features to further improve model performance.

