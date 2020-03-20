# -Detecting-Fake-News-using-Python
Detect Fake News using TfidfVectorizer and train model using  PassiveAggressiveClassifier
First I load data using pandas then we split data into training and testing datasets.
Then I use TfidfVectorizer, The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features where Tf means Term Frequency
and idf means Inverse Document Frequency.
Then I use PassiveAggressiveClassifier algorithm to train our data and predict using this machine learning algorithm.
Then I predict out test dataset and got 93.60 % accuracy.

News Dataset link::- https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view
