# gene-classification

The steps:
step 1. Creating the matrix for control group
step 2. Creating the matrix for disease group
step 3. creating a dictionary object where each key is the class value and then add a list of all the records as the value in the dictionary.
step 4. Assuming that the samples are drawn from guassian distribution, We need two statistics from a given set of data. The two statistics we require from a given dataset are the mean and the standard deviation (average deviation from the mean).
step 5. Now it is time to use the statistics calculated from our training data to calculate probabilities for new data.

Probabilities are calculated separately for each class. This means that we first calculate the probability that a new piece of data belongs to the first class, then calculate probabilities that it belongs to the second class, and so on for all the classes.


