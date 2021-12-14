# Multiclass Classification of Products for Sale

## Project Description
We plan to use a publicly available dataset from a Kaggle competition hosted by the Otto Group in 2015. The Otto Group, a multinational retailer selling millions of products, needs to classify products consistently and correctly in order to analyze how different product types are selling. The project aims to classify new and existing products into nine groups based on their characteristics. 

## Motivation
Seeking to automate product classification is not unique to the Otto Group; Amazon uses the Product Classifier software to help sellers assign their merchandise to one or many product categories (Shankar et al., 2011). However, this software package is costly for many small and medium e-business companies. Thus, developing open-access machine learning algorithms that aid in automating product classification can help small businesses reduce their costs. Additionally, consistent classification of products enables companies to more easily analyse product performance to gain business insights. Once successfully implemented, our classifier will be able to automatically categorize tens of thousands of products.

## Project Plan
We plan to tackle our multiclass classification problem by exploring multiple classification algorithms. We will begin our modeling process by performing exploratory data analyses and preparing our data to maximize our prediction power. We plan to employ and compare multiple approaches, such as oversampling and undersampling, to address the imbalanced class labels. Furthermore, as no additional information about the 93 attributes of the current dataset is available (i.e., whether or not redundant or irrelevant features exist in the set, etc.), we propose to use various methods, such as Principal Component Analysis, to reduce the dimensionality of our expansive feature space. Lastly, k-fold cross-validation will be utilized for hyper-parameter tuning. We will execute this project plan using scikit-learn, a software machine learning library (Pedregosa et al., 2011).
