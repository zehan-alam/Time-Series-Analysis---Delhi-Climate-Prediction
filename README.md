## Delhi Daily Climate Data Analysis

I conducted an analysis on a dataset comprising daily climate information for Delhi spanning from 2013 to 2016 for training data and 2017 for testing data. The training data consists of 1461 entries, while the test data contains 114 entries.

### Methodology
- **Data Exploration:** Utilized visualizations to assess the data, revealing noticeable seasonal patterns.
- **Machine Learning Algorithms:** Employed various regression algorithms including LGBMRegressor, XGBRegressor, CatBoostRegressor, and RandomForestRegressor.
- **Model Selection:** Identified the best-performing regressor by comparing RMSEs.
- **Parameter Tuning:** Optimized model parameters to enhance performance using RandomizedSearchCV.
- **Evaluation:** Concatenated the training and test data and visualized predictions to evaluate model effectiveness.
