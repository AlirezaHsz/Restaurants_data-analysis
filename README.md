# Restaurants_data analysis
In this project, the main idea is to explore and find restaurants in Rafsanjan to start a bussiness. The main idea is to classify the restaurants into subclassses ranging from A to E as customer satisfaction score. This measure will help us to make decisions about our bussiness in future.
So the goals to achive are:
## 1) Data collection: 
In this step we have collected the data about the restaurants in Rafsanjan using google. The dataset includes information such as Restaurant's name,Rate, Number of Reviews, Address, Location.
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/ab6da7dd-6dcf-416f-87cd-e781930a92a8)

## 2) Data prepration and statistics: 
In this step we have cleaned and prepared the data using python:
Results:
The dataset has 166 rows and 4 columns.
We have 113 rows with Rating and Reviews columns being filled.
The average of the Ratings and Reviews is 4.10, and 6.15, respectively.
The minimum of Ratings and Reviews is 1, and 1, respectively. 
The maximum of Ratings and Reviews is 5, and 100, respectively. 
We have 53 rows with NULL values to be removed.
There are no duplicated records even with duplicated names.
Added a new column as a metric named “Customer Satisfaction Score”.
Added a new column named “Street” that was obtained from the Address column for later analysis.
The average rating for Rafsanjan is 4.11.
The Percentage of Positive Reviews for Rafsanjan is 65.49%.

## 3) Data visualization:
### A. Python visualizations
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/bd6805b9-a7bb-4044-8fa6-f35ba1e27686)
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/ce720341-3a53-4f10-80ac-5f3eb86adf89)
### B.PowerBI visualizations
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/5d17be19-6820-4cdf-8f6e-8e352cd22f47)
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/4b9e4f5c-c483-43eb-a050-1cdc9526a4c3)
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/70837170-a79e-403a-9d49-e73bee3bcbe5)
![image](https://github.com/AlirezaHsz/Restaurants_data-analysis/assets/137410544/3c35be9e-f907-4c19-8f9c-1c664afe24c0)
## 4) Data storage by SQL Server:
Created a database named dbRafsanjan.
Created a table named Restaurant.
All 113 records were entered into the table.
## 5) Findings:
Starting with the restaurants with “A” or “B” scores.
Considering the Review number as some of the scores seem not to be valid.
Monitoring the Average Rating KPI while growing the network of new restaurants as the initial value was 4.11 and trying to increase this value.
Monitoring the Positive Reviews Percentage KPI as the initial value was 65.49% and trying to increase this value. 
Streets like Taleghani and Motahari seem to be a good choice to start activities as they have 18 and 15 restaurants respectively.















