# *An introduction to data science project*

##### *student name*: Yosef Danan

## part 1:

this part discuss about plots in matplotlib and seaborn libraries.

the dataset contains information about apps in apple store and our task was to visualize the data
(so we can learn more about the data)

## part 2:

this part discuss about run supervised learning algorithm from scikit-learn library on one dataset from Kaggle, I choose google play apps dataset and my goal was to predict whether or not apps will success, my definition to "success" app was above 1M installs, and to make it more interesting I also defined something in the middle called "good" app that was above 200k.

my features to predict was:

**size** in megabytes of the app
**Type** that tells if app is paid or free(0 or 1)
general **Category** of the app(between 0 to 12)
**Content Rating** that tells the audience that fit to the app(teen, everyone etc.)

and choose to ignore the **Rating** and **Reviews** features because we know at the end(when we also know the installs numbers).

just to remind **The null hypothesis** was that all 3 states of success(great , good and failed) distribute uniformly namely that non of the features above not influencing the success state

Part of my models shows good result:

**K-Nearest Neighbors** with 92% accuracy score
**Decision Tree** with 88% accuracy score (after k fold cross validation method(with 5 folds))
**Random Forest** with 88% accuracy score
**Gaussian Naive Bayes** with 84% accuracy score
**Support vector machines** with 91% accuracy score
**Adaptive Boosting** with 90% accuracy score

part of them shows really bad result:

**Logistic Regression** with 26%
**Neural Network** with 39%

