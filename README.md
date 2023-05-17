# Mercedes-Benz-Green-Manufacturing

The company's engineers have developed a robust testing system to ensure the safety and reliability of every unique car configuration before they hit the road. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

This dataset from Kaggle contains different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz's standards.

# One hot encoding method
One-hot encoding is used with the assumption that there is no hierarchical nature of the categorical variables X0 to X8. Due to the high-dimensional nature of the dataset, one-hot encoding is expected to have a lower R-squared value. As such, the models have to be trained on the top 19/20 with the highest mutual information scores. The highest score for the training CV R^2 is 0.59, and the highest test submission score is 0.53858 with the XGBoost and CatBoost ensemble learning implementation.

# Label encoding method
Label encoding helps to signficantly reduce the dimensional space. The notebooks will be added soon.
