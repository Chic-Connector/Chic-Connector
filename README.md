"""
The Movie Review Sentiment Analysis project aims to create a robust machine
learning model for evaluating and predicting the sentiment (positive or negative)
expressed in movie reviews. The entire process is implemented in a google collab
using Python and involves various stages from data acquisition to analysis and
visualization. The primary dataset utilized is sourced from IMDb, encompassing
both positive and negative movie reviews. Key libraries such as Pandas, NumPy,
Matplotlib, Seaborn, and Scikit-learn are employed to facilitate data handling,
exploration, and modeling.

The project initiates with the importation of essential libraries, loading of
the IMDb dataset, exploration of sentiment distribution, and preprocessing of
text data. Enhancement of the project was given in the another code which
includes the application of the TF-IDF vectorizer for feature extraction and the
utilization of a Support Vector Machine (SVM) classifier for modeling.
The model's performance is further optimized through hyperparameter tuning using
GridSearchCV. The final steps include model training, evaluation of accuracy,
and visualization of sentiment predictions.

This project provides a comprehensive framework for sentiment analysis,
applicable not only to IMDb but also adaptable to other movie review platforms
like Rotten Tomatoes. By incorporating standard practices in machine learning,
it seeks to establish a reliable model for discerning sentiment in movie reviews.

Special thanks goes to ACL (Association for Computational Linguistics) for
providing a set of 25,000 highly polar movie reviews for training, and 25,000
for testing. the Raw text was an already processed bag of words contained in the
file.

REFERENCE
Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and
Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th
Annual Meeting of the Association for Computational Linguistics (ACL 2011)."""

