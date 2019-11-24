## Amazon Cell Phone Review Analysis and Rating Predictions

In this project, I analyzed Amazon cell phone reviews and predicted the rating for the cell phones using the reviews. This dataset focuses on both unlocked and locked carriers, and scoped on ten brands: ASUS, Apple, Google, HUAWEI, Motorola, Nokia, OnePlus, Samsung, Sony, and Xiaomi.

There are two files in this dataset: 
1. Cell phone information data and 
2. Cell phone review data. 
The dataset can be downloaded from __[here](https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews)__.

I analyzed the data for below given points:
1. Review Analysis
2. Popular Review Words
3. Brand-wise Review Rating
4. Date-wise Review Count
5. Predicting Rating Based on Reviews

### Summary of Results
1. Majority of the reviews have less than 100 words.
2. Samsung is the most popular cell phone brand with most number of models.
3. Predominant positive words in the reviews: great, love, brand new, works great, negative words: issue, problem, bad, still.
4. Majority of popular 20 frequent words are positive.
5. We can see that Mototola, Samsung and ASUS have most of the ratings above 3, while brands like Nokia, Sony, Apple and Google have ratings distributed from 2 to 5.
6. Review count has consistently increased from 2010 to August 2019 and reduced after that. Maximum number of reviews are seen in July 2019.
7. We got the best accuracy of cell phone rating prediction using Linear SVC Model.

To view the code and graphs accurately, please click on __[this link](https://nbviewer.jupyter.org/github/phtelang/Data-Passion/blob/master/Amazon%20Cell%20Phone%20Review%20Analysis%20and%20Rating%20Predictions.ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the csv datasets on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
