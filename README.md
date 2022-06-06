# homework2-Knowledge-Discovery

This homework is the Sentiments Analysis on Twitter dataset. Since that our dataset is unbalanced (Negative Class is majority rather than Positive one), we did three 
attempts to proceed with our analysis: the first attempt is to balance test and validation set, the second one is to use the Weighted Cross-Entropy Loss and the third
one is to do undersampling. So, we did three notebooks for each of these attempts. After that we choose the best techinique to do our analysis by taking the epoch with
the highest Average Validation Accuracy for each attempt and at the end by choosing again the one with the highest Average Validation Accuracy and considering also the 
Average Test Accuracy.
