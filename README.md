# TwitterSentiment
It is a Natural Language Processing Problem where Sentiment Analysis is done on X data using diffrent Machine Learning algorithm

# About Dataset
Dataset is taken from kaggle there are around 27000 tweets of three classes positive , negative , neutral due to computataion power I dropped all the neutral tweets data and train the model only on 1000 samples . However i also trained model in all three classes which you can see in rough notebook where i have done lots of experiment like hyper parameter tuning diffrent method to convert words into vectors and so on.

# Results
| Model | Accuracy | Recall|
| --- | --- | --- |
| LogisticRegression | 0.83 | 0.86|
| SVC | 0.83 | 0.82|
| VotingClassifier | 0.83 |0.84