# cervical_cancer_classification
The "Cervical Cancer Classification" project is aimed at developing a machine learning model to classify cervical cancer based on various medical attributes and risk factors.
## Description:
This project demonstrates the potential of machine learning in assisting medical professionals in the early detection of cervical cancer. By achieving a high F1 score, the model shows promise in accurately classifying cancer cases and contributing to better patient care.

## Key Steps and Insights:
**1. Data Preprocessing:** The project begins with loading and preprocessing two main datasets: movie ratings and movie information. This involves cleaning and structuring the data for further analysis.

**2. Data Exploration:** The project encodes movie genres into binary columns using the one-hot encoding technique, making it easier to incorporate genre information into the recommendation system.

**3. Handling Imbalanced Data:** The release year of each movie is extracted from the movie titles, and the titles are cleaned to remove the year information.

**4. Building the Model:** The project constructs a movie-user rating matrix, where movies are on one axis, users on the other, and each cell represents a user's rating for a specific movie. Missing values are filled with zeros.

**5. Model Evaluation:** The project includes data visualization to understand the distribution of user votes for movies and the number of votes by users.

