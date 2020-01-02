# Quora-question-pair-similarity
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

> Credits: Kaggle

### Objective 
To predict whether a pair of questions are duplicates or not.

### Data Source 
https://www.kaggle.com/c/quora-question-pairs

### Model Used
<ul><li>
Try out models (Logistic regression, Linear-SVM) with simple TF-IDF vectors .
<li>Perform hyperparameter tuning of XgBoost models using RandomsearchCV with vectorizer as TF-IDF W2V to reduce the log-loss.
