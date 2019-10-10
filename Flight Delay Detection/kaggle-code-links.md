## All the kaggle notebooks
- https://www.kaggle.com/aishakhatun/final-notebook-and-analysis

The final notebook. With the correct features.

- https://www.kaggle.com/aishakhatun/catboost-with-more-features

The features I used were the same as the solution notebook. Infact, in the solution notebook weather information was wrongly set. From the feature importance graph we see that the weather information isnt even required(after setting correctly). so we get rid of them. Then the 'minute' feature was set as category once, and another time as int(as in solution). The 'int' version could beat the baseline.

- https://www.kaggle.com/aishakhatun/feature-creation-and-catboost

This is the last notebook just before competition ended. To this point, on failing to find any usefull feature, I merged several pairs of features, removed the highly correlated features, and then after training once, also removed the irrelevant, or comparatively less relevant features from the feature importance graph(to prevent over-fitting). This didnt get any higher than 77/78 on validation set. The reason is `overfitting`. With the slightest task of changing `minutes` feature from `int` to `categorical` started overfitting.

- https://www.kaggle.com/aishakhatun/random-forest

Testing out random forest in this kernel

- https://www.kaggle.com/aishakhatun/catboost-starter-features

Initial notebook.

- https://www.kaggle.com/aishakhatun/lgboost

Tried lgboost. Incomplete notebook

- https://www.kaggle.com/aishakhatun/catboost

Catboost with cv. Incomplete.
