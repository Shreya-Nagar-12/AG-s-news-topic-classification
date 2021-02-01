# AG-s-news-topic-classification
Data set link : https://www.kaggle.com/amananandrai/ag-news-classification-dataset
AG's News Topic Classification :

1) Basic data preprocessing is done by checking presence of missing values and class imbalance problem.

2) Text Cleaning is done to-
	i) Retaing only chracters/ removing punctuation,numbers.
	ii)Converting data to lower case.
	iii)Lemmatization - Reducing inflected words to their meaniningful stem word. Also, Lemmatiztion is used instead of stemming because stemming doesn't reduce inflected words to         meaningful word stem. 

3) Term Frequency & Inverse Document Frequency (TF IDF) is used for Feature Extraction (converting textual data to vector) because-
	- It retains word importance information (high or less important word).
	- It performs better on machine learning algorithm.

4) Fitting Random Forest and Multinominal Naive Bayes model.

5) Evaluating model with accuracy Multinomial Naive Bayes gave better result.
