== Description ==

This program is used to compare two ensemble algorithms, namely
Random Forest and AdaBoost in detecting hoax news about the covid-19 vaccine.
By using 2 test scenarios, namely data scenarios and classification scenarios.

- In the data scenario, 3 data types are used, namely "Title", "News Content", and a combination of "Title + News Content".
- In the classification scenario, 2 algorithms are used, namely Random Forest and AdaBoost.

The data will later go through preprocessing steps such as Case Folding,
Removing Punctuation, Stopword, Tokenizing and Stemming.

To test the data, a preprocessing test of the data will be carried out with 2 scenarios, namely:
- test scenarios using full preprocessing
- test scenarios without using stopwords and stemming
the 2 test scenarios will be processed through Word2Vec feature extraction, hyperparameter tuning,
as well as the calculation of the confusion matrix evaluation to determine the algorithm and the best accuracy values ​​obtained from the 2 scenarios.