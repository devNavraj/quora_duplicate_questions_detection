# quora_duplicate_questions_detection
Quora is a place to gain and share knowledge - about anything. It is a platform to ask questions and connect with people who contribute unique insights and quality answers. Enormous number of users on the Quora website makes it inevitable to have multiple questions from different users with similar intent, which raises the issue of duplicate questions. Duplication of questions ruins the experience for both the questioner and the answerer. In this work, Quora Question Pairs dataset is collected from Kaggle for detection of duplicate questions. The goal of our project is to present the results of systematic and comparative experimentation for automatic duplicate question detection, when different types of methods are applied to the dataset. I have explored and applied different machine learning and deep learning techniques on the task of identifying duplicate questions on Quora’s question pair dataset. 

By using feature engineering, feature importance techniques, and experimenting with four selected Machine Learning classifiers, we demonstrated that our models outperformed previous studies on this task. Random Forest classifiers with Word2Vec vector features and character level Term Frequency and Inverse Document Frequency (TF-IDF) are our best machine learning models that have also outperformed a few of the deep learning baseline models. We applied deep learning techniques to model four different deep neural networks of multiple layers consisting of Glove embeddings, Long Short Term Memory (LSTM), Dense, Batch Normalization, Activation functions, Gaussian Noise and model merged with commutative operations. Our deep learning models achieved better accuracy than machine learning models. Our best model achieved accuracy of 91.32% which is better than most models studied before.
# SOFTWARE AND TOOLS
I have used the python programming language and its various libraries to implement our project. Some major libraries that will be used in our project are listed below:
1. Pandas: For data preprocessing and feature engineering
2. NLTK: For data preprocessing, especially cleaning and tokenizing
3. Gensim: To implement the Word2Vec model which provides an in-built utility for
finding similarity between two words given as input by the user.
4. Scikit-learn: For feature engineering and building the machine learning models.
5. Xgboost: To create the xgboost model that implements Gradient Boosted
Decision Trees algorithm.
6. Tensorflow: To build deep learning models.
7. Keras: To provide a python interface for tensorflow libraries.
