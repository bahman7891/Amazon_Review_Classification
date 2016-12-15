## Amazon_Review_Classification
![alt tag](http://i.stack.imgur.com/B9VWLm.png)


Using various machine learning algorithms we classify ratings. 
There are two ipython notebooks for each product. one analyzes the bag of bi-grams and the other analyzes bag of words.

The notebooks should be self explanatory and run smoothly. 
Each notebook contains processor class which processes the data and the rest are modeling.The data are in this [here] (http://www.cs.jhu.edu/~mdredze/datasets/sentiment/) (the file is called processed_stars).

The vocabulary of the train data after stop words removed is over 15600 (ref. the Vocab notebook).

1st notebook (Project_ML_NLP_Bahman_Roostaei) is for bag of words for book reviews.

2nd notebook (Project_ML_NLP_Bahman_Roostaei-2) is for bag of bi-grams for book reviews.

3rd notebook (Project_ML_NLP_Bahman_Roostaei-3) is for bag of words for DVD reviews.

4th notebook (Project_ML_NLP_Bahman_Roostaei-4) is for bag of bi-grams for DVD reviews.

5th notebook (Project_ML_NLP_Bahman_Roostaei_Vocab) is showing the vocabulary size of books and DVD reviews.

The details and discussions are inside the notebook. However the model comparison shows that gradient boosting results in a very high F1 score and the best ROC curve (in the case of regression). Based on this support vector does not seem to be necessary although we have tried and concluded that svc does not improve the gradient boosting.

