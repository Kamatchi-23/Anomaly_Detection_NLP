# Anomaly_Detection_NLP
This project employs NLP techniques at basic level to build sentiment classifiers and in turn analyze its behavior as Anomaly detector.
Objective:
The objective here is to build a model that is able to clearly distinguish the sentiments and thereby predict Anomaly records appropriately, so it is equally important to keep both Precision and Recall scores very high. Hence, it is very much significant to achieve a higher F1 score. 

Steps Involved:
•	Data Extraction 
•	Data Preprocessing
•	Data cleaning and Text pre-processing 
•	Visualized reviewText using Word cloud
•	Converting text data into vectors 
•	Split data into train and test set
•	Develop base model
•	Hyperparameter Tuning
•	Final model 
•	Model Validation 

Observations & Conclusions:
For a given dataset, the best sentiment classifier may not necessarily turn out to perform the same in the case of Anomaly classification. Here, a high F1 score for Sentiment Classification was achieved by the Multinomial Naïve Bayes model. However, when it comes to Anomaly classification, Logistic Regression model has given the highest F1 score.
In order to further improve the performance of anomaly classification (achieving negligible or zero cases of False Negatives), following points can be taken into consideration as part of future work:
1.	For the analysis, only 1-star and 5-star ratings were considered as representation of the negative and positive sentiments respectively and trained model accordingly. In future, 1-star, 2-star & 3-star records could be grouped under Negative sentiment and 4-star & 5-star records under positive sentiment. 
2.	Further, advanced embedding techniques, NLP libraries like Spacy, Genism or Neural network techniques and models like BERT, LSTM could be utilised for the project implementation with an expectation to achieve zero cases of False Negatives.

Business Recommendation:
The recommendation to the Business would be to have recommendation system based on the Anomalies identified by our model. This system could send messages, mail or a call to their customers and suggest them to re-examine the feedback provided. This process is expected to improve the credibility of the ratings for a product and provide better user experience, especially for new customers. This way businesses can draw data-driven insights to analyse the gaps and take necessary steps to boost their sale



