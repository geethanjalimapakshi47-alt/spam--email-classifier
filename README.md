****Spam Email Classifier using Machine Learning****

Objective:

The objective of this project is to build a Spam Email classification system using Machine Learning techniques that can automatically detect whether a message is spam or ham (not spam). The system helps improve message filtering accuracy and reduces phishing and scam risks by classifying text messages using NLP techniques.

 Technologies Used:

Python, Pandas, NumPy, Scikit-learn, TF-IDF Vectorizer, Logistic Regression, Matplotlib, Seaborn

 Methodology:

The dataset is collected and preprocessed by cleaning the text data. This includes converting text to lowercase, removing URLs, numbers, special characters, and extra spaces.

After preprocessing, TF-IDF Vectorization is applied to convert text data into numerical features. The dataset is then split into training and testing sets.

A Logistic Regression model is trained on the training data to classify messages as spam or ham. Finally, the model is evaluated using accuracy, classification report, confusion matrix, and ROC-AUC score.

 Model Performance"

The Logistic Regression model achieved an accuracy of 97.48% and a ROC-AUC score of 98.27%, showing strong performance in distinguishing between spam and ham messages.

 Insights:

Spam messages often contain words such as free, win, prize, claim, urgent, and verify. These patterns are strong indicators of spam. Logistic Regression performs well for text classification tasks and provides reliable results for real-world message filtering.

 How to Run:

Clone the repository and install the required libraries. Run the Jupyter Notebook or Python file. After running the model, enter any message and the system will predict whether it is spam or ham.

 Example Predictions:

Input: “Win free lottery now”
Output: SPAM

Input: “Hey are we meeting tomorrow”
Output: HAM

Input: “Your account will be blocked verify immediately”
Output: SPAM

 Visualizations:

Add the following screenshots in your GitHub repository:

Confusion Matrix
ROC Curve
Model Accuracy Output
Prediction Results

These help visualize model performance clearly.
<img width="1840" height="667" alt="dataset" src="https://github.com/user-attachments/assets/7cd9bf02-0f9e-4490-960f-41e9214d69db" />
<img width="1600" height="1204" alt="cleaned data" src="https://github.com/user-attachments/assets/62a10498-0f91-4208-ab03-259b50a2d84e" />
<img width="1600" height="1204" alt="evaluation matrix" src="https://github.com/user-attachments/assets/f42bc089-4a3f-4ca8-add0-1258f9c096c0" />
<img width="1600" height="1204" alt="confusion matrix" src="https://github.com/user-attachments/assets/8255b3c6-673f-4cb2-9910-88c01ada4538" />
<img width="1600" height="1204" alt="roc score" src="https://github.com/user-attachments/assets/a3cd3ef6-e87c-44e2-986e-d03d039ab482" />
<img width="1599" height="899" alt="output" src="https://github.com/user-attachments/assets/1a655c40-94e3-40d5-9e58-827ad1e3c245" />

 Conclusion

The project successfully builds a machine learning-based spam detection system using TF-IDF and Logistic Regression. The model achieves high accuracy and effectively classifies spam and ham messages. This system can be used for real-world applications such as email filtering and phishing detection.
