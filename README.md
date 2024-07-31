This project combines data science and social science methodologies to investigate food insecurity in Suffolk County, Massachusetts, focusing on urban American food systems and socio-economic factors. 

It utilizes Random Forest, a machine learning algorithm, to analyze demographic data from census tracts and determine their levels of correlation with food insecurity rates. 

The scikit-learn Random Forest Classifier is used to build the model in Python. I employ max-features, which is the maximum amount of features considered by the model before “splitting a node” (making a decision),
mini_sample_leaf, which selects the minimum amount of leaves needed to split an internal node (decisions within decision), max_leaf_nodes, which allows the maximum leaf nodes in each tree (leaf nodes being points in which further decision splitting cannot be done thus resulting in a final outcome),
and n_estimators, which is the amount of trees built by the model before finding the average of all the predictions.

NumPy library is used to graph a Variable Importance chart of various demographic statistics, with food given from the MAPC using Feeding America and Greater Boston Food Bank data. 

The findings reveal significant relationships between Median Household Income, race demographics, unemployment, and food insecurity rates, highlighting the complex interplay of socio-economic factors in determining access to food. 
This suggests an influence of low wages, systemic racism, and lack of employment opportunities for individuals in Suffolk County. 

The paper also discusses the potential of machine learning in social science research and suggests avenues for future exploration to address food insecurity effectively.
