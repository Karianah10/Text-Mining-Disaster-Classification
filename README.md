# Text Mining: Tweet Classification (Disaster vs. Non-Disaster)

This is a repository for my data science portfolio project on tweet classification using text mining techniques. The goal of this project is to build a machine learning model that can classify tweets as either related to a disaster or non-disaster.

## Dataset
The dataset used for this project is sourced [kaggle](https://www.kaggle.com/competitions/nlp-getting-started/data), which consists of a collection of labeled tweets. Each tweet is labeled as either a disaster or non-disaster tweet. The dataset includes various features, such as the tweet text, location, and other relevant metadata.

## Workflow
1. Data Preprocessing: Perform necessary preprocessing steps on the raw tweet text, including removing stopwords, tokenization, and handling special characters.
2. Feature Extraction: Extract relevant features from the preprocessed tweet text, such as TF-IDF, word embeddings, or n-grams, to represent the tweets numerically.
3. Model Training: Train various machine learning models on the extracted features, such as logistic regression TF-IDF & W2V, and Naive Bayes TF-IDF
4. Evaluation: Evaluate the trained models using appropriate evaluation metrics, such as accuracy, precision, recall, F1-score, or ROC-AUC.
5. Model Selection: Select the best-performing model based on evaluation results. 
6. Testing: Testing model on unlabelled dataset.

## Results and Findings
After training and evaluating various models, the best-performing model achieved an accuracy of 79% on the test set, which is the model built with TF-IDF logistic regression algorithm. The model showed good precision and recall for both disaster and non-disaster tweets, indicating its effectiveness in classifying tweets correctly.

Through the analysis of misclassified tweets, we discovered that certain patterns or linguistic nuances pose challenges in classification, requiring further exploration and improvements in future iterations of the model.

## Conclusion

This project demonstrates the application of text mining techniques for tweet classification, specifically distinguishing between disaster and non-disaster tweets. The trained model can be valuable in real-world scenarios, such as identifying and prioritizing relevant tweets during crisis management or assisting in sentiment analysis for social media monitoring.


If you have any questions, suggestions, or feedback, feel free to reach me out at [email](karianah10@gmail.com) or [linkedin](https://www.linkedin.com/in/karianah/).

Happy exploring and classifying tweets!
