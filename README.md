# classification-toxic-comments
Multi-label NLP classification of toxic comments using the Kaggle Jigsaw dataset.

Pipeline : text cleaning → TF-IDF → SMOTE → Logistic Regression & Naive Bayes.
Labels : toxic, severe_toxic, obscene, threat, insult, identity_hate.
Models : Logistic Regression (main) + Multinomial NB.
Metrics : Accuracy, F1-score, ROC-AUC, confusion matrices.
Best performance : up to 0.98 AUC depending on label.
Output : submission_softmax.csv.
