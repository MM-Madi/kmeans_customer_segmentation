# Customer Segmentation (Clustering) using K-Means - Conformed with Statistical Significance tests

In this project I use an **unsupervised learning** method to solve a problem of **customer segmentation**. Using the **k-means** model for clustering I locate and classify customers that have similar consuming behaviour (spending habits) according to their characteristics. I check and confirm the results from the exploration and the clustering phases using different **statistical tests** including **t-tests**, **one-way anova** and **Tukey’s HSD**.

In this (business) context the goal is to identify different sub-groups in the customer database that could be, for example, targeted by different marketing strategies.

In the data exploration phase I combine <ins>descriptive statistics, visualisation and significance checks</ins> to understand the data, identify significant features and potential clusters. The data contains demographic information (Customer ID, age, gender, annual income) as well as information concerning consuming behaviour represented by a **Spending-Score**.

<img width="459" alt="income_score_gender_graph" src="https://user-images.githubusercontent.com/99167342/188332351-1e3f2152-70dd-4912-9bda-cbf36a0474c3.png">

In accordance with model metricies, visualisation and following confirmation with statistical tests, segmentation on two features were identified as follows:

1. Based on the **Annual_Income** measure five segments of customers were identified that are defined according to a combination of their tendancy (High/Low) on both their annual income and their spending score:
* <u>High-Low:</u> Income above 70k and Score under 40
* <u>Average-Average:</u> Income between 40k-75k and Score between 35-60
* <u>High-High:</u> Income above 70k and Score above 60
* <u>Low-Low:</u> Income under 40k and Score under 40
* <u>Low-High:</u> Income under 40k and Score above 60

<img width="491" alt="clusters" src="https://user-images.githubusercontent.com/99167342/192160661-4a93b010-b467-4953-bb29-b23f480551cf.png">

2. Based on the **Age** measure two segments of customers were identified:
* <u>Under</u> 40 years old
* <u>Above 40</u> years old

Data: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python.
