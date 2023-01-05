#CPU Processing Hack Detection

###This project aims to detect hacking activities based on CPU processing information.


##Solution
We propose to use a machine learning algorithm, specifically a Random Forest Classifier, to analyze patterns in CPU processing usage and other relevant features such as memory processing, total processors running, and the difference between memory and CPU processing. A labeled dataset will be used to train the classifier, and standardized evaluation metrics will be used to evaluate its performance.

The implementation of this solution will be done in Python, using the following libraries:

`Pandas: for loading and manipulating the data`
`NumPy: for numerical computing`
`Scikit-learn: for training and testing the classifier`
`Matplotlib: for visualizing the results`


##Future Goals

In the future, we plan to explore the use of other machine learning algorithms, such as XGBoost, for the ML work. We believe that this may further improve the accuracy and robustness of our model.

A larger system that can capture and analyze CPU processing data in real-time and warn users of any potential hacking activity is what we also plan to integrate this approach .

