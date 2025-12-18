# Movie Genre Classification using Machine Learning

## Objective
To build a machine learning model that predicts the genre of a movie based on its plot description.

## Dataset
Movie genre dataset provided by CODSOFT in text format, containing movie descriptions and corresponding genres.

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

## Methodology
1. Parsed raw text data to extract genre and movie description
2. Label encoded movie genres
3. Converted text data into numerical features using TF-IDF
4. Split the dataset into training and testing sets
5. Trained a Logistic Regression model for multi-class classification
6. Evaluated the model using accuracy and classification report

## Results
The Logistic Regression model achieved an accuracy of approximately **58%** on the test dataset.

## Discussion
The achieved accuracy is reasonable given the multi-class nature of the problem, class imbalance among genres, and overlapping movie themes.

## Conclusion
This project demonstrates the application of machine learning techniques for multi-class text classification and highlights real-world challenges such as imbalanced data and genre ambiguity.
