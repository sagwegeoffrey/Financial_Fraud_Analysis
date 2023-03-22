# Financial_Fraud_Analysis

Due to rapid growth in cashless transactions, the chances of number of fraudulent transactions can also increase.Fraud 
transanctions can be identified by analyzing various behaviors of credit card customers from previous transactions history 
datasets. We develop a basic understanding of risk analytics in banking and financial services and understand how data is used
to minimize the risk of losing money while lending to customers. Based on the analysis, the credit card transaction dataset is
very skewed, there are much fewer samples of frauds than legitimate transactions. To stop fraud before losses occur we use 
machine-led detection (Supervised Learning), SMOTE for imbalanced/skewed dataset and self-learning capabilities(Autoencoders) 
that quickly adapts as new threats emerge and scale to minimize end-to-end fraud prevention.

Due to data security and privacy, different banks are usually not allowed to share their transanction datasets. These 
problems make fraud detection system (FDS) difficult to learn the patterns of frauds and also difficult to detect 
them ~ Solution--> We propose a framework to train a fraud detection model using behavior features with federated learning, we term this
detection framework  FFD (Federated Learning for Fraud Detection). FFD enables banks to learn fraud detection model with the training data 
distributed on their own local database. Using Federated Learning it improves prediction accuracy of the data. A shared FFD is constructed by 
aggragating locally-computed updates of fraud detection model. Banking institutions can collectively reap the benefits of shared model without 
sharing the dataset and protect the sensitive information of cardholders.
