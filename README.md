# LongLeadExtremePrecipitationForecasting
Use Machine Learning to implement long lead extreme precipitation forecasting (5-15 days) for the state of Iowa using the historical meteorological data of the whole Northern Hemisphere (5,328 locations) over 30 years (1980-2010) and the historical spatial average precipitation data of the state Iowa from the same time period.
•	Data preprocessing: Construct data samples in the proper format for machine learning algorithms from raw data. The feature space for predicting the atmospheric regimes is huge and complex. The number of features contributing to the regimes, from the Cartesian product between the spatial and temporal domains, is enormous. Worked with almost half million features.
•	Feature selection: Process of selecting a subset of relevant features for use in ML model construction. Implemented using SAOLA - Scalable and Accurate OnLine Approach.
•	Machine learning models: Train and evaluate various ML classification models. Precipitation clusters that can trigger extreme floods are rare. They happen once per year or once per several years in a certain region. This causes an extreme imbalance in data. Dealt with imbalanced data problem using techniques such as undersampling, oversampling, SMOTE - Synthetic Minority Oversampling Technique etc. Various classification models such as SVM (Support Vector Machine), Naive Bayes, XGBOOST (eXtreme Gradient Boosting) has been used.
