# Smart-Resume-Classifier-Machine-Learning-Based-Resume-Categorization
# Project Description
This project focuses on building a machine learning pipeline to classify resumes into job categories such as HR, IT, Marketing, and more. The goal is to automate the process of sorting resumes, helping recruiters and HR professionals efficiently manage large volumes of candidate applications.

# Overall Goal
Classify resumes into relevant job categories using traditional machine learning models, primarily Support Vector Machines (SVM) and K-Nearest Neighbors (KNN).

# Flow of the project
Load Data
Load the resume dataset containing raw text and their corresponding job categories.

Text Preprocessing
Clean the text by removing noise such as URLs, special characters, and converting text to lowercase.

Feature Extraction
Convert cleaned resumes into numerical vectors using TF-IDF vectorization, highlighting the importance of words across resumes.

Label Encoding
Convert textual category labels into numerical values using LabelEncoder for compatibility with ML algorithms.

Model Training
Train classifiers like SVM and KNN on the vectorized resume data.

Evaluation
Evaluate model performance using accuracy, precision, recall, and F1-score metrics.

Prediction
Use the trained model to predict categories of new, unseen resumes.

# Key Code Highlights
Text Cleaning:
Custom cleaning function using regular expressions to remove URLs and special characters ensures text quality.

TF-IDF Vectorization:
Converts text into a fixed-size vector representation suitable for ML models.

Label Encoding:
Transforms category labels into integers for classification.

Model Training:
SVM with a linear kernel is used for its effectiveness in high dimensional text data.

Evaluation Metrics:
Accuracy and classification reports provide insights into model performance.

# Model Performance
Among the models tested, Support Vector Machine (SVM) achieved the best accuracy in classifying resumes, making it the preferred choice for this task due to its ability to handle high-dimensional textual data efficiently.
