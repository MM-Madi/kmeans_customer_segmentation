# Customer Segmentation (Clustering) using K-Means - Confirmed with Statistical tests

In this project I use an **unsupervised learning** method to solve a problem of **customer segmentation**. Using the **k-means** model for clustering I locate and classify customers that have similar consuming behaviour (spending habits). I check and confirm the results from the exploration and the clustering phases using different **statistical tests** including **t-tests**, **one-way anova** and **Tukey’s HSD**.

In this (business) context the goal is to identify different sub-groups in the customer database that could be targeted by different marketing strategies.
The data contains demographic information (Customer ID, age, gender, annual income) as well as information concerning consuming behaviour represented by a **Spending-Score**.

<img width="424" alt="pair_plot" src="https://user-images.githubusercontent.com/99167342/193678300-bbb4e1d6-9311-4267-8ec5-6fc96ba1541a.png">

<ins>Segmentation on two features were identified as follows:</ins>

1. Based on the **Annual_Income** measure five segments of customers were identified that are defined according to a combination of their tendancy (High/Low) on both their annual income and their spending score:
* <ins>High-Low:</ins> Income above 70k and Score under 40
* <ins>Average-Average:</ins> Income between 40k-75k and Score between 35-60
* <ins>High-High:</ins> Income above 70k and Score above 60
* <ins>Low-Low:</ins> Income under 40k and Score under 40
* <ins>Low-High:</ins> Income under 40k and Score above 60

<img width="504" alt="income_score" src="https://user-images.githubusercontent.com/99167342/193678477-0a1e6077-b705-4fa4-a568-3ed79c6d1c03.png">

2. Based on the **Age** measure two segments of customers were identified:
* <ins>Under</ins> 40 years old
* <ins>Above 40</ins> years old

<img width="493" alt="age_score" src="https://user-images.githubusercontent.com/99167342/193678648-2d4861f0-02e9-4a8f-b80d-1522b5251388.png">

Data: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python.
