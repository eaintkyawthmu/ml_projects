# ml_projects
Caltech AIML Machine Learning Projects

Mercedes-Benz Greener Manufacturing .
Course-end Project 1

DESCRIPTION

Reduce the time a Mercedes-Benz spends on the test bench.

Problem Statement Scenario:
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.

To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

You are required to reduce the time that cars spend on the test bench. Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

Following actions should be performed:

If for any column(s), the variance is equal to zero, then you need to remove those variable(s).
Check for null and unique values for test and train sets.
Preprocess categorical features
Perform dimensionality reduction.
Predict your test_df values using XGBoost.
Find the datasets in repo under "project_1" folder.

------------------------


Income Qualification .
Course-end Project 2

DESCRIPTION

Identify the level of income qualification needed for the families in Latin America.
Problem Statement Scenario:
Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.
In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling or the assets found in their homes to
classify them and predict their level of need.
While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.
The Inter-American Development Bank (IDB)believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.
Following actions should be performed:
Identify the output variable.
Understand the type of data.
Check if there are any biases in your dataset.
Check whether all members of the house have the same poverty level.
Check if there is a house without a family head.
Set poverty level of the members and the head of the house within a family.
Count how many null values are existing in columns.
Remove null value rows of the target variable.
Predict the accuracy using random forest classifier.
Check the accuracy using random forest with cross validation.
Find the datasets and data dictionary in the repo under "project_2" folder.

------------------------

Health Care .
Course-end Project 3

DESCRIPTION

Cardiovascular diseases are the leading cause of death globally. It is therefore necessary to identify the causes and develop a system to predict heart attacks in an effective manner. The data below has the information about the factors that might have an impact on cardiovascular health. 
To download the complete document and dataset in the repo under "project_3" folder.

------------------------
Book Rental Recommendation.
Course-end Project 4

DESCRIPTION

Book Rent is the largest online and offline book rental chain in India. They provide books of various genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. 
Project Objective:
You, as an ML expert, should focus on improving the user experience by personalizing it to the user's needs. You have to model a recommendation engine so that users get recommendations for books based on the behavior of similar users. This will ensure that users are renting the books based on their tastes and traits.
Note: You have to perform user-based collaborative filtering and item-based collaborative filtering.
Dataset description:
BX-Users: It contains the information of users.
user_id - These have been anonymized and mapped to integers
Location - Demographic data is provided
Age - Demographic data is provided
If available, otherwise, these fields contain NULL-values.
 
BX-Books: 
isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from the dataset.
book_title
book_author
year_of_publication
publisher

 
BX-Book-Ratings: Contains the book rating information. 
user_id
isbn
rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.
 
Note: Download the “BX-Book-Ratings.csv”, “BX-Books.csv”, “BX-Users.csv”, and “Recommend.csv” using the link given in the Book Rental Recommendation project problem statement.
 
Following operations should be performed:
Read the books dataset and explore it
Clean up NaN values
Read the data where ratings are given by users
Take a quick look at the number of unique users and books
Convert ISBN variables to numeric numbers in the correct order
Convert the user_id variable to numeric numbers in the correct order
Convert both user_id and ISBN to the ordered list, i.e., from 0...n-1
Re-index the columns to build a matrix
Split your data into two sets (training and testing)
Make predictions based on user and item variables
Use RMSE to evaluate the predictions
 
To download the dataset in the repo under "project_4" folder.


