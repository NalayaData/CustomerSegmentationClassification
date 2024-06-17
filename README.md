# CustomerSegmentationClassification
This repository contains our solution for the [Classifying Customers into Segments](https://www.kaggle.com/competitions/classifying-customers-into-segments/overview) challenge originally published on Kaggle.
In this project, we explore the data, define the machine learning problem, and provide a solution to classify customers into existing segments. Additionally, we propose a model for re-segmenting customers using clustering techniques.
The project is composed from 3 main notebooks :

1. CustomerSegmentationClassification_Part_1 : Exploratory Data analysis and in depth analysis of missing data
2. CustomerSegmentationClassification_Part_2 : Data preprocessing and machine learning experiments for classifying customers into existing segments
3. CustomerSegmentationClassification_Part_3 : Customer Segmentation Using Data Clustering
   
# Dataset Description

The [dataset]((https://www.kaggle.com/competitions/classifying-customers-into-segments/overview)) is made available on Kaggle by Tanmay Nema, vedarth kumtekar (2023) .The following are the composition of Data for the Competition:
- Training Dataset (train.csv)
- Testing Dataset (test.csv)
  
The Datasets is composed from the below list of columns:
  - ID: Unique ID
  - Gender: Gender of the customer
  - Ever_Married: Marital status of the customer
  - Age: Age of the customer
  - Graduated: Is the customer a graduate?
  - Profession: Profession of the customer
  - Work_Experience: Work Experience in years
  - Spending_Score: Spending score of the customer
  - Family_Size: Number of family members for the customer (including the customer)
  - Var_1: Anonymised Category for the customer
  - Segmentation: Target -> Customer Segment of the customer
