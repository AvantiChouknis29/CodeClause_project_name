# CodeClause_SpamClassifier
Developed a ML model which is able to classify Spam/Ham emails.
Dependencies used-numpy & pandas.
Scikit-learn is mainly coded in Python and heavily utilizes the NumPy library for highly efficient array and linear algebra computations.It supports Logistic regression.Scikit-learn works nicely with numerous other Python packages, including SciPy, Pandas data frames, NumPy for array vectorization, Matplotlib, seaborn and plotly for plotting graphs, and many more.
train_test_split function is used to split data into training(80%) and testing(20%).
TfidVectorizer is used to transform text to numerical values[enhances machine performance by converting text to numeric value].
Imported LogisticRegression model and accuracy score to find out accuracy of model (stated 97.62%).

Process-1:Data collection & Pre-processing:
-Reads .csv file by using pandas library and converting into dataframe.
-Replaces all null values with a null string.

Process-2:Label Encoding:
Spam-0
Ham-1
-Using .loc in which we specify category and then give encoding as 0/1.
-Separate data as texts/labels
X-Message (emails)
Y-Category (Spam/Ham encoding)

Process-3:Spliting data into Training Data(80%)  & Test Data(20%) using test_split

Process-4:Converting text data into feature vectors (numerical values).

Process-5:Feed data into Logistic Regression Model.

Process-6:Evaluating our model using .predict().
-On training and testing data accuracy score is measured.

Process 7:
-Final part building prediction system where you can enter a mail and model uses .transform & .predict to  transform & predict is the mail spam/ham.

