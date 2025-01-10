# What should be Bellabeat's marketing strategy?

## Used Software
- Python
- Jupyter Notebook
  - pandas
  - matplotlib
  - numpy

## Scenerio
This is a fictional scenario where I am working as a Junior Data Analyst for a fictional company, Bellabeat.

Bellabeat is a high-tech manufacturer of health-focused products for women and is a successful small company with potential to become a larger player in the global smart device market. Our Chief Creaative Officer believes analyzing smart device fitness data could help unlock new growth opportunities for the company.

I have been asked to focus on one of Bellabeat's products and analyze smart device data to gain insights into how consumers are using their smart devices. The insights I discover will assist in guiding the marketing strategy for the company. I will present my analysis to the Bellabeat executive team along with my high-level recommendations for Bellabeat's marketing strategy.

**Products**

- **Bellabeat App** - The Bellabeat app provides users with health data related to their activity, sleep, stress, menstual cycle, and mindfukness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness prodicts.
- **Leaf** - Bellabeat's classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.
- **Time** - This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.
- **Spring** - This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.
- **Bellabeat Membership** - Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty, and mindfulness based on their lifestile and goals.

## Introduction
I have been asked to focus on one of Bellabeat's products and analyze smart device data to gain insights into how consumers are using their smart devices.

I am working with the assumption that we have enough data to generalize the data to the population of smart device users.

To guide this project, I have come up with a few questions:
1. In the two months of data we have available, how active are the users using these smart devices?
2. What purpose do people use these smart devices?

## Preparation
To prepare, I downloaded a dataset available through a public domain, made available through [Mobius](https://www.kaggle.com/datasets/arashnic/fitbit/data) to conduct this case study.

Looking through the reports, it seemed there was really only one csv that had full data -- dailyActivity_merged. The data contains two months from 35 different users of FitBit tracker data that we will use to describe the purpose people use their smart devices.

Using the Python Pandas package, I read in the data and began to clean and prepare.
To begin, I checked and fixed any columns that did not have correct data types. I also standardized the column names to snake-case for readability. I also added columns to show which day of the week was recorded for a later analysis.

I checked for duplicate rows and null values, which there were none, removed columns I would not use in the analysis, and filtered out impactful outliers to finish off the data preperation process.

## Analyze
- Aggregate data
- Organize and format data
- Perform calculations
- Identify trends and relationships

## Share
- Determine the best way to share findings
- Create effective data Visualizations
- Present Findings

## Recommendations
- Share recommendations

