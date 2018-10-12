# codefundo
The United States Geological Survey (USGS) is of the opinion that scientists will never be able to predict earthquakes accurately. They can at most say that an earthquake will hit a place some time in the future, but not exactly when. 

However, big data analytics is providing a leap in the accuracy of earthquake predictions, with recent predictions being 90 percent accurate.

In recent years, powerful computational techniques to analyze big data have emerged, making possible the analysis of massive datasets. 
When such big datasets must be analyzed, computational resources increase and traditional machine learning algorithms require new parallelized implementations that must be launched in clusters. 

The methodology used to carry out the proposed regression study is as follows. A large amount of earthquake events are retrieved, divided and used to train and test a set of machine learning algorithms in a comparative way. The whole procedure is sustained by a big data infrastructure placed in a public cloud. 
A set of four machine learning-based regressors are used to carry out the regression study: generalized linear models (GLM), gradient boosting machines (GBM), deep learning (DL) and random forests (RF).
Every regressor is trained using each training dataset producing a regression model. Models were then applied to each testing dataset resulting on earthquake predictions. All predictions are compared with their corresponding actual values producing a set of deviations. Such deviations are evaluated resulting on absolute and relative errors.
