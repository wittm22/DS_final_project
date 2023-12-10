# DS_final_project

## Boston Marathon Winners (Men and Women)
The Boston Marathon, the world's oldest marathon, is a prominent race that runners from all over the world travel afar to compete in. This 26.2 mile race started in 1897 and has taken place almost every year since then. I found datasets on Kaggle which contain the male and female winners from each year's Boston Marathon. The datasets include the name of the winner, they year in which he/she won, the country he/she is from, his/her finishing time, and the distance of the race in both miles and kilometers. 

By analyzing the datasets, I wanted to answer the following research questions:

1. What is the average time distance between men and women?

The men's winner has always been faster that the women's winner for every Boston Marathon, so I wanted to see the average difference in winning times for the Boston Marathon. 

2. Has marathon times overall decreased over time?

I wanted to see if the winning times have gotten faster over time. 
From 1897 to 1923, the marathon was 24.5 miles long, and from 1924 onward, the marathon was 26.2 miles long. Thus, I am going to find the overall trends in winning times from 1897 to 1923, and then separately, trends in winning times 1924 and later. 

3. Ranking countries on how many boston marathon winners they have

Runners travel from all around the world to participate in this prestigious race, so I want to determine the distribution of countries that the Boston marathon winners are from. 

4. How many people have won the boston marathon multiple times?

I want to see the likelihood of someone winning the Boston marathon more than once.

5. Mean difference in finishing time after distance change

I want to determine the average finishing time for the years when the Boston Marathon was 24.5 miles long (1897 - 1923) compared to when the Boston Marathon was 26.2 miles long (1924 - present). 

6. What 5 years resulted in the fastest fininshing times for men and women?

I want to analyze which five years had the top finishing times for both the men's marathon and women's marathon. I want to see if there is any overlap in the years with some of the fastest times. 

Methodology:
In order to analyze the datasets, I will be using python code in Juptyer Notebook. 
Some tools I will be using to create visualizations based off the dataset are NumPy, Seaborn, Pandas, and Matplotlib

datasets found on kaggle: https://www.kaggle.com/datasets/zhikchen/boston-marathon-winners-men-and-women


I would like to determine the overall trend in marathon times from the first marathon in 1897 to the present time. I will use a linear regression model to figure this out. 

