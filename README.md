# cervical_cancer_classification
The "Cervical Cancer Classification" project is aimed at developing a machine learning model to classify cervical cancer based on various medical attributes and risk factors.
## Description:
This project demonstrates the potential of machine learning in assisting medical professionals in the early detection of cervical cancer. By achieving a high F1 score, the model shows promise in accurately classifying cancer cases and contributing to better patient care.

## Key Steps and Insights:
**1. Data Preprocessing:** The project begins with loading and preprocessing the dataset. Missing values denoted by '?' are replaced with NaN, and columns are converted to the appropriate data types.

**2. Data Exploration:** Exploratory data analysis is performed to understand the distribution of categorical and numerical features. This includes visualizations such as count plots for categorical features and density plots for numerical features.

**3. Handling Imbalanced Data:** The project identifies class imbalance in the target variable ('Dx_Cancer') and recognizes the need for balancing techniques to improve model performance.

**4. Building the Model:** A Random Forest Classifier is chosen as the classification model. Hyperparameters for the Random Forest are defined, and the model is trained on the preprocessed data.

**5. Model Evaluation:** The model's performance is evaluated using the F1 score, a common metric for binary classification tasks. The F1 score quantifies the trade-off between precision and recall.
