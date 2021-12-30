Income Qualification Project
DESCRIPTION
Identify the level of income qualification needed for the families in Latin America.
Problem Statement :
Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.
In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling or the assets found in their homes to
classify them and predict their level of need.
While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.
The Inter-American Development Bank (IDB)believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

•	Identify the output variable.
•	Understand the type of data.
•	Check if there are any biases in your dataset.
•	Check whether all members of the house have the same poverty level.
•	Check if there is a house without a family head.
•	Set poverty level of the members and the head of the house within a family.
•	Count how many null values are existing in columns.
•	Remove null value rows of the target variable.
•	Predict the accuracy using random forest classifier.
•	Check the accuracy using random forest with cross validation.




Procedure
At first we explored the dataset, identifying the target, understanding the data type.
Then we would change the object variables in numeric.  We find the variable with 0 variance. We find the bias. We checked if there are families with no head. We found columns with null values and fixed them.  We set the poverty level for rural and urban areas. Then applying standard scaling we found the Accuracy rate.


Answers….
1. Our Target variable is Target
2.  We have mixed data types. float64 8 variables, int64 130 variables ,  object  5 variables
3. There are biases.
4. Done
5.  There are houses without family head
6.  Done
7. There are null values in some columns
8. Done
9. Accuracy is 90%
10. Done
