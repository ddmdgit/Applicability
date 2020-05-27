# Applicability.

Check the applicability of the mobile learning system.

There are three algorithms included in this repository (01.Apriori, 02.FP Growth, 03-Novel BTPM).

These algorithms are developed to run on Jupyter notebook.

In Algorithm - 03 BTMP

in line 4, minFUT (threshold for minimum feature usage in a transaction) has to be given.

in line 16, number of transaction rows of dataset has to be given.

in line 113, 8 should be replaced according to the value of the length of the ArrayFeature. I didn't automate it. It can be don simply assigning a variable to length of the ArrayFeatures (n=len(ArrayFeatures))
