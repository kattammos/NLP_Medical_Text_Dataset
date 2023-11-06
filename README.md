# NLP_Medical_Text_Dataset

The dataset includes cancer documents to be classified into three categories: colon cancer = 2579, lung cancer = 2180, thyroid cancer = 2810, 

I will use NLP to cluster this document. I first do data cleaning, then tokenization, then using stopword I remove frequent words and do lemmatization. 
Then I train the data with: LogisticRegression, MultinomialNB, GaussianNB, BernoulliNB. 

### Conclusion:
A text document with a maximum word count of over 30000 words contains 3 categories: thyroid cancer, lung cancer and colon cancer. 
After processing the data, the text was reduced to 30000 words. 

Models I'm training: LogisticRegression, MultinomialNB, GaussianNB, BernoulliNB 

LogisticRegression predicts better, train 96%, test 94%. 
