# NLP_Behold_Project_dso560_2021spring_Team_Gold
Behold partnered with USC’s DSO-560 NLP class to collaborate on an analytics problem.  

## This project has two objectives:

1. Create a classification algorithm to predict `brand_name` given a product's information (part A)
2. Build a recommender algorithm to recommend a complete outfit given a customer's search query (part B)

The code to achieve each objective is available in 5 Jupyter Notebooks in this repository.

## Part A: Getting predictions of brand name
Within the scope of this project, we consider only the top 30 brands which feature most often in the dataset. The remaining brands were labeled as `Other` and the models were built to predict one of the 31 labels (30 brands + `Other`).
