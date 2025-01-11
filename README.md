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

I am working with the assumption that we have enough data to generalize the data to the population of smart device users, and that it covers a wide range of active individuals.

In this case study, I focus on analyzing the smart device data from Bellabeat users to uncover insights into consumer activity and behaviors. This analysis aims to inform marketing strategies by understanding user activity levels, potential target demographics, and how Bellabeat’s products align with customer needs.

## Preparation
To prepare, I downloaded a dataset available through a public domain, made available through [Mobius](https://www.kaggle.com/datasets/arashnic/fitbit/data) to conduct this case study.

Looking through the reports, it seemed there was really only one csv that had full data -- dailyActivity_merged. The data contains two months from 35 different users of FitBit tracker data that we will use to describe the purpose people use their smart devices.

Using the Python Pandas package, I read in the data and began to clean and prepare.
To begin, I checked and fixed any columns that did not have correct data types. I also standardized the column names to snake-case for readability. I also added columns to show which day of the week was recorded for a later analysis.

I checked for duplicate rows and null values, which there were none, removed columns I would not use in the analysis, and filtered out impactful outliers to finish off the data preperation process.

## Analyze & Share
- Aggregate data
- Organize and format data
- Perform calculations
- Identify trends and relationships

Since the comppany offers fitness products, the first thing that comes to mind is to figure out how active are the users of these smart devices? It turns out, according to our sample of data, smart device users are not that active.

![Average Minutes by Activity Level]()

This may be the case overall, but I wasn't convinced this would be the case for every day of the week since office workers have more free time on weekends. As it turns out, the pattern stays consistent, so we have evidence that the smart device users aren't very active. 

![Activity Level By Day Of Week]()

Since I understood the demographic now, I was looking for any trends connected to minutes active, and was able to find a correllation between total steps taken and minutes active. It seems the more minutes active for eache activity level, the more steps were taken, while the more sedentary minutes, the less steps taken.

![Total Steps By Active Minutes]()

Similarly, based on the data, we were able to uncover a correlation between minutes active and calories burned. It seems for each activity level, the more active you are, the more calories you burn, and the more sedentary you are, the less calories you burn.

![Calories Burned By Active Minutes]()

Finally, based on the data, it seems there is a positive correlation between total steps and calories burned, meaning there is evidence to show more steps you take, the more calories you burn.

## Recommendations
It seems, based on our data, fitness smart device users are not very active. There seems to be a positive relationship between total steps taken and calories burned as well. Based on this, I would suggest one of the following:
1. Market to Lightly Active People: The data suggests the majority of users are “lightly active” and thus would benefit from motivation to be more active. This group could be an untapped opportunity for Bellabeat’s products to offer more personalized activity and goal-setting features.
2. Target Weight-Loss Enthusiasts: Position Bellabeat products as tools for easy weight loss management, focusing on effortless ways to increase daily steps and improve overall wellness.

## Conclusion
By understanding the activity patterns and correlating behaviors of our customers, Bellabeat has the opportunity to grow its customer base by appealing to lightly active individuals and those looking for a low-effort way to achieve health goals like weight loss. Tailored marketing campaigns and product enhancements could help fill these needs and create new growth opportunities.
