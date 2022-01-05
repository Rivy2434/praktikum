# Classification of toxic comments 

## Description
This project aimed to create a model which can distinguish toxic and non-toxic comments with a minimum F1 score of 0.75.
Labeled data contains text comment in text and target in toxic.
For feature engineering, TF-IDF was used. Following libraries were used: pandas, nltk, sklearn, matplotlib, lightgbm, torch, spacy

## Results

Data were preprocessed (stopwords and cymbols were removed). TF-IDF values of words were used as features. The best F1 score was achieved for linear regression model trained on uni- and bigramms.
