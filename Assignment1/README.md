# Medical Insurance Cost Prediction (AI-ML Assignment 1)

**Name:** Akshat Kumar Singh  
**Registration Number:** 23BCE11120  
**Application Number:** IN26011815 
**Email:** singhakshat1225@gmail.com  

## Objective
To develop a Multiple Linear Regression model that estimates the medical insurance charges of customers based on their personal and health-related information[cite: 1].

## Dataset Link
[Kaggle: Medical Cost Personal Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)[cite: 1]

## Libraries Used
* Pandas (Data manipulation)
* Scikit-Learn (Model building and evaluation)
* Matplotlib (Data visualization)

## Methodology
1. **Data Understanding:** Identified numerical features, categorical features, and the target variable (`charges`)[cite: 1].
2. **Data Preprocessing:** Checked for null values, applied One-Hot Encoding to categorical variables, and split the data into 80% training and 20% testing sets[cite: 1].
3. **Model Development:** Trained a Multiple Linear Regression model on the training set[cite: 1].
4. **Model Evaluation:** Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared metrics, alongside an Actual vs. Predicted scatter plot[cite: 1].

## Results
* **Mean Absolute Error (MAE):** *4181.19*
* **Mean Squared Error (MSE):** *33596915.85*
* **R-squared Score:** *0.7836*

## Conclusion
This assignment successfully deployed a Multiple Linear Regression model to predict medical insurance charges[cite: 1]. The primary key findings indicate that insurance costs are predominantly driven by a customer's smoking status, which serves as the most critical risk factor[cite: 1]. Additionally, an individual’s age and Body Mass Index (BMI) also significantly elevate the estimated insurance charges, whereas region and children have a lesser effect[cite: 1]. 

One notable limitation of applying Linear Regression to this specific medical dataset is its inherent assumption that all independent variables operate independently of one another[cite: 1]. In reality, health factors are often highly correlated. For example, the detrimental health effects of smoking are often compounded exponentially when combined with a high BMI. Because a basic linear model adds these features independently, it struggles to capture these complex, synergistic interactions, thereby limiting its predictive accuracy for high-risk patients.
