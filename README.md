# Association_Groceries
Association Analysis on Grocery List in Python
# The Data
The data was provided onthe public data section on Kaggle.  The goal of this exercise is to find association rules with the grocery items in the dataset.  Association Analysis is a data mining technique used to find patterns of one or more events (antecedent) with another event (consequent).  This is commonly used in market analysis to discover and predict consumer purchasing behavior by observing what items are likely purchased with others.  
# The algorithm
Support:  Support is the number of occurances of the item or group of items divided by the total number of occurances.  The minimum threshold for support in this exercise is set to .0003.  The the frequent item list is created for the analysis. 
Confidence:  Confidence is how many times the consequent occurs when the antecedent occurs.  The minimum threshold is set to .05.
Lift:  Lift is a parameter that is needed to account for high support of the consequent.  If the consequent is very frequent then the association rule is less meaningful.  The Lift formula is Confidence/(Support of the Consequent).  The lift parameter is used to show more meaningful rules.  The lift parameter is set to miniumum of 3.0.  
# Results
71 Rules are discovered with mimumum lift value of 3 and minumum confidence value of .05
