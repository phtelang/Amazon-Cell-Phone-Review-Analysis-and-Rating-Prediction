## Amazon Cell Phone Review Analysis and Rating Prediction

In this project, I analyzed Amazon cell phone reviews and predicted the rating for the cell phones using their reviews. This dataset focuses on both unlocked and locked carriers, and scoped on ten brands: ASUS, Apple, Google, HUAWEI, Motorola, Nokia, OnePlus, Samsung, Sony, and Xiaomi. Using the data, I analyzed the reviews, brand and date-wise review differences and predicted the cell phone ratings using reviews. 
I used four models for prediction: LogisticRegression(), RandomForestClassifier(), MultinomialNB(), LinearSVC(). 
- Logistic Regression is a classification algorithm. Logistic regression transforms its output using the logistic sigmoid function to return a probability value which is used for prediction.
- Random Forest algorithm performs both classification and regression tasks using ensembling. Ensembling is done by training multiple decision trees on different data samples built by replacement. It combines the predictions of multiple models to create a more accurate final prediction. One of the major advantages of random forests over single decision trees is that they tend to overfit less. 
- A Naive Bayes classifier is a probabilistic machine learning model that is used for classification task. Using Bayes theorem, we can find the probability of A happening, given that B has occurred. The assumption made here is that the predictors/features are independent. Hence it is called naive.
- Support Vector Classifiers tries to construct the best hyperplane to separate a dataset into different classes in the best possible way by maximizing the distance between sample points and the hyperplane. Based on the hyperplane, it predicts the output.

There are two files in this dataset which can be downloaded from __[here](https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews)__

### Summary of Results
1. Majority of the reviews have less than 100 words.
2. Samsung is the most popular cell phone brand with most number of models.
3. Predominant positive words in the reviews: great, love, brand new, works great, negative words: issue, problem, bad, still.
4. Majority of popular 20 frequent words are positive.
5. We can see that Mototola, Samsung and ASUS have most of the ratings above 3, while brands like Nokia, Sony, Apple and Google have ratings distributed from 2 to 5.
6. Review count has consistently increased from 2010 to August 2019 and reduced after that. Maximum number of reviews are seen in July 2019.
7. An accuracy of 73% was achieved for the cell phone rating predictions using Linear SVC Model.

To view the code and graphs accurately, please click on __[this link](https://nbviewer.jupyter.org/github/phtelang/Data-Passion/blob/master/Amazon%20Cell%20Phone%20Review%20Analysis%20and%20Rating%20Predictions.ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the csv datasets on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
