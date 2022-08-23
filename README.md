# Heart Disease UCI
In this project, I trained machine learning models using python to detect if a person has heart disease or not.
I used a [dataset](https://github.com/navjeet-py/Heart-Disease-UCI/blob/main/heart.csv) that contains various health related features of people and every person is labelled if they has health disease or not.

First of all, I loaded the data in a pandas dataframe. Then performed some basic data analysis. Drew a corelation heatmap between all the features and labels.
Then I added some extra features based on the features which had larger co-relation with the label to enhance their effect. Finally, split the dataset into training and test sets and trained some models using various 
machine learning algorithms (like SVM, logistic regression, K-neighbours classification) and neural networks. 

I was able to get an accuracy of 92% with the SVM model.

### Libraries used-
1. Pandas
2. Scikit-Learn
3. Matplotlib
4. Tensorflow
