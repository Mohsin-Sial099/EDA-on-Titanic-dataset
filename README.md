# EDA-on-Titanic-dataset
# <p style="font-family:Bradley Hand ITC;font-size:150%;text-align:center;color:#1ECBC7;">Discription of Dataset</p>
**Two main subsets are included in the Titanic data set: a training set (855)train.csv and a test set (855)test.csv The result of each passenger's survival or no survival shall be reported in the training set, which serves as a basic fact. This set is used to build machine learning models, leveraging features such as gender, ticket class and potential engineered aspects. However, the results of the tests are not available, and the task is to predict the survival of each passenger using a trained model**

**A sample submission file (gender_submission.csv) is included, demonstrating predictions where only female passengers are assumed to survive, offering guidance on the format of the submission file**

# <p style="font-family:Bradley Hand ITC;font-size:100%;color:#1ECBC7;">Data Dictionary</p>

1. Survival represent Binary indicator (0 for No, 1 for Yes)
2. Pclass represent Ticket class representing socio-economic status (1 for 1st, 2 for 2nd, 3 for 3rd)
3. Sex represent Gender of the passenger
4. Age represent Age of the passenger in years (fractional if less than 1, and in the form of xx.5 if estimated)
5. Sibsp represent Number of siblings/spouses aboard the Titanic
6. Parch represent Number of parents/children aboard the Titanic
7. Ticket represent Ticket number
8. Fare represent Passenger fare
9. Cabin represent Cabin number
10. Embarked represent Port of Embarkation (C for Cherbourg, Q for Queenstown, S for Southampton)

# <p style="font-family:Bradley Hand ITC;font-size:100%;color:#1ECBC7;">Variable Notes</p>

* Pclass represents socio-economic status, categorized as Upper (1st), Middle (2nd), and Lower (3rd) class.
* Age represents Fractional if less than 1, with estimated ages denoted as xx.5.
* Sibsp & Parch represents Define family relations, including siblings, spouses, parents, and children. Some children traveled solely with a nanny, leading to a parch value of 0 for them.

**This dataset offers a rich array of features for predictive modeling, encouraging exploration and analysis to uncover insights regarding survival patterns aboard the Titanic**
