# Week-Eleven-Lab-Repository
This is repository dedicated to storing code that has been taken from lab twelve, which can be meant for future reference.

##  Lab 11: Document Clustering and Analysis using Custom K-Means
For this lab, you will use a different subset of the 20 Newsgroup data set that you used in the lab 9. The subset for this 
dataset includes 2,500 documents (newsgroup posts), each belonging to one of 5 categories Windows (0), Crypt (1), Christian (2), 
Hockey (3), Forsale (4). The documents are represented by 9328 terms (stems). The dictionary (vocabulary) for the data set is given in
the file "terms.txt" and the full term-by-document matrix is given in "matrix.txt" (comma separated values). The actual category 
labels for the documents are provided in the file "classes.txt". Your goal in this lab is to perform clustering on the documents and 
compare the clusters to the actual categories.

For this lab, DO NOT use the KMeans clustering function in scikit-learn. You may use Pandas and other modules from scikit-learn that 
you may need for preprocessing or evaluation.
