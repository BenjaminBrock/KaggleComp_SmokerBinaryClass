# READ ME

This project started as a University assignment - aimed at exploring a known machine learning model and applying to any given dataset problem.
Having already worked with all of the models included, it felt more appropriate to use all of them and observe their different performances.

From observation - there was a clear ceiling on the efficacy of these models, whatever metric was chosen to assess them. This ceiling was also prevalent in most other submissions found.
This is likely due to 2 factors:

* The data is synthetic and generated from a significantly smaller sample size.
* The features recorded within this data set may not be the ideal measurements to use. A quick google search provides the following article from the national library of medicine - indicating that urine cotine levels could be a far superior feature, missing from the data set.

Overall, this was an enjoyable exploratory task and also allowed for a better unerstanding of the hardware requirements of each model. For example, runing an SVC model on a dataset with so many features is significantly more computationally heavy than the random forest when handling the higher feature sets.

