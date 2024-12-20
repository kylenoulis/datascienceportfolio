# Data Science Project Portfolio

This repository showcases a collection of projects completed as part of the University of Texas Data Science and Business Analytics certification program. Each project demonstrates the application of various data science techniques and methodologies, including supervised and unsupervised learning, model tuning, and statistical analysis. These projects highlight the practical skills and knowledge gained throughout the certification program.

See below for a summary of each project and direct link to the project file.

## [Statistics](https://github.com/kylenoulis/datascienceportfolio/blob/main/Statistics/eNews_notebook.ipynb)

Verified the effectiveness of a new landing page on user engagement and new subscriber conversion. This experiment was conducted on a sample of 100 users, split evenly into a control and treatment group. Univariate and bivariate analysis was conducted on the dataset to determine engagement. Hypothesis tests were performed to validate the results of the experiment, leading to the conclusion that the new landing page is more effective at driving engagement and converting subscribers.

## [Supervised Learning - Regression](https://github.com/kylenoulis/datascienceportfolio/blob/main/ML/Supervised/Regression/Notebook.ipynb)

Investigated the sale of refurbished and used cellular devices to determine the factors that influence device sales in order to maximize profit. This was conducted by fitting the data to a linear regression model. Prior to creating the regression, the data was explored and treated for missing values. Feature engineering was performed due to the wide variety of device characteristics and pricing. Devices were grouped into categories, replacing a generic brand_name variable. The price value was normalized to create low, mid, and high range categories. A linear regression model was created and then checked for multicollinearity, with variables being dropped from the model as necessary.

## [Supervised Learning - Classification](https://github.com/kylenoulis/datascienceportfolio/blob/main/ML/Supervised/Classification/Notebook.ipynb)

Analyzed hotel bookings to uncover trends and factors influencing cancellations and no-shows. Univariate and bivariate exploratory data analysis methods were employed to gain insights. The dataset was meticulously examined for missing values, and feature engineering was conducted to address data anomalies. A logistic regression model was trained, followed by the development of a decision tree. Feature importance was assessed to determine the necessity of pruning.

## [Unsupervised Learning](https://github.com/kylenoulis/datascienceportfolio/blob/main/ML/Unsupervised/Presentation.pdf)

Analyzed stock market data for a financial consultancy firm to determine the best approach for maximizing returns for its customers. Along with exploratory data analysis, two different clustering models were created: K-Means and Hierarchical. Each model was evaluated to find the optimal number of clusters, and then each cluster was grouped into an investment strategy based on its level of overall risk.

## [Model Tuning](https://github.com/kylenoulis/datascienceportfolio/blob/main/ML/Tuning/Presentation.pdf)

Built, tuned, and compared a series of models to determine the most accurate in successfully predicting machine failure for a wind energy company. Six models were built from the original data: Logistic Regression, Bagging, Decision Tree, AdaBoost, Gradient Boost, and Random Forest. Recall value was used as the scorer to cross-validate and hyperparameter tune, resulting in four hypertuned models: Gradient Boosting with oversampled data, AdaBoost with oversampled data, Random Forest with undersampled data, and XGBoost with oversampled data. Of these, the XGBoost produced the best fit between the training and validation datasets.

