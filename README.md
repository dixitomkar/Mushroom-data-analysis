# Mushroom-data-

1. Data Set: Mushroom Data Set
The problem is to determine what makes a mushroom edible or not-edible. This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like ``leaflets three, let it be'' for Poisonous Oak and Ivy.

Objective: As noted in the writeup, there are edible, poisonous and unsure mushroom samples. Unsure samples have been labeled as poisonous in the data set. Your job is to analyze the mushroom data set and see if you can’t find the subset of poisonous samples which correspond to unsure class. You will need samples marked both edible and poisonous to make this determination.

There are 8124 records with 22 attributes, some having missing attributes.

You will need to divide your data set into a training set and a test set. Use samples of 50-50, 60-40, and 70-30 for the training-test ratios

Try plotting the data using several plotting functions to see what it looks like. Use pairs (e.g., 2D plots) or 3 variables (3D plots) based on the packages. 

Try to filter the data by selecting samples with only certain attribute values and plotting them.

You should try data reduction to eliminate some attributes through Principal Components Analysis. The idea is to try and select N attributes that will help you focus on identifying the unsure samples.
