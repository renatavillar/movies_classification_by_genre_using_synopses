# MPST-Movies-Classification-by-Genre
Given a dataset with movies id with its plot synopses and genre(s), we construct machine learning algorithms to classifiy new movies by genre. We use two models: Multinomial Naive Bayes Classifier and Decision Tree Classifier. We got a better performance with Decision Tree Classifier, even without hyperparameters tuning.

After testing the tree's depth for values from 10 to 60 nodes, we got the best performance in the Decision Tree model with 39 nodes, obtaining a F1 score equal to 0.5212087839738564.
