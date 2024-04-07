Naive Bayes Algorithm from scratch.





Required Data Set Format for Naïve Bayes
Columns (0 through N)

0: Instance ID
1: Attribute 1
2: Attribute 2
3: Attribute 3
…
N: Actual Class
The program then adds two additional columns for the testing set.

N + 1: Predicted Class
N + 2: Prediction Correct? (1 if yes, 0 if no)


Breast Cancer Data Set
This breast cancer data set contains 699 instances, 10 attributes, and a class – malignant or benign (Wolberg, 1992).

Modification of Attribute Values
The actual class value was changed to “Benign” or “Malignant.”
Transformed the attributes into binary numbers so that the algorithms could process the data properly and efficiently. If attribute value was greater than 5, the value was changed to 1, otherwise it was 0.

Missing Data
There were 16 missing attribute values, each denoted with a “?”. Chosed a random number between 1 and 10 (inclusive) to fill in the data.
