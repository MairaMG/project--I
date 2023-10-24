# Project-1-Pandas
## Overview
This aim of this project is to clean and format a dataset containing information about shark attacks, and use the data to produce visualizations that will either prove or disprove my hypotheses.
## Requirements/Libraries Used:
This code was written in Python/Jupyter Notebook, using the following libraries:

Numpy
Pandas
matplotlib.pyplot
Seaborn

Data Source: https://www.kaggle.com/teajay/global-shark-attacks

## 1. Hypotheses:

TEMPORAL TRENDS OF SHARK ATTACKS & GEOGRAPHICAL

1- Shark attacks has been increasing over the years

2- Sharks attacks happened mostly in summer

DEMOGRAPHIC ANALYSIS

3- Sharks attacks more younger men than older women 

ACTIVITY ANALYSIS

4- The activity that causes more shark attacks is surfing

## 2. Data Pre - Cleaning Documentation

1. Handlelign missing values
2. Standardize text by deleting spaces and transforming values to lower
3. Drop columns with more than 99% missing values and empty rows
4. Cleaning of all the columns I wanted to work with: Case_Number, Year, Type, Country, Activity, Sex, Age, Injury, Fatal, Species.
5. Saving into .csv format

## 3. Data Cleaning Documentation

1. Double checking missing values
2. Handling categorization for Fatal column (just 2 values: Yes/No)
3. Saving into .csv format

## 4. Analysis

### 1) Shark attacks has been increasing over the years
To identify patterns in the frequency of shark attacks over the years, which could be vital for understanding whether incidents are increasing, decreasing, or remaining stable.

![Image1](https://github.com/MairaMG/project--I/blob/main/images/1.Shark_Attacks_per_year.png)

From the chart, it seems like there is a general trend of increasing shark attacks over the years. However, it is not very clear, so the next step was to grouped years by decades to have a more clear visualization of the trend over time.

### 1.1) How has the number of shark attacks changed over the decades?

![Image2](https://github.com/MairaMG/project--I/blob/main/images/2.shark_attacks_by_decade.png)

From the plot, it can be observed a general increase in the number of shark attacks in the 1950 to 1960 and from the 2000 to the 2020. The increase in recorded incidents could be due to a variety of factors, including increased human activity in shark habitats, improved reporting and data collection, climate change and overfishing and an actual increase in the number of shark attacks.

### 1.2) Which countries have the highest number of shark attacks?

![Image3](https://github.com/MairaMG/project--I/blob/main/images/1.shark_attacks_by_decade_and_country.png)

In this plot, I've selected the top 10 countries to make the visualization easier.

-The USA consistently has a high number of shark attacks across all decades.
-Australia also has a significant number of incidents, especially in the mid-20th century.
-Other countries contribute to a lesser extent to the total number of incidents.

This plot provides a visual representation of the distribution of shark attacks over time and broken down by country.

### 2) Sharks attacks happened mostly in summer

![Image4](https://github.com/MairaMG/project--I/blob/main/images/3.Shark_Attacks_per_month.png)

The increase in shark attacks during the summer months could be attributed to a variety of factors, including higher water temperatures, increased human activity in water, and seasonal migration patterns of sharks.

Understanding the patterns can be crucial for public safety and awareness, especially in regions where shark attacks are more common.

DEMOGRAPHIC ANALYSIS 

### 3) Sharks attacks more younger men than older women 

![Image5](https://github.com/MairaMG/project--I/blob/main/images/3.shark_attacks_by_age_gender.png)

The distribution is slightly left-skewed, indicating that younger individuals are more frequently involved in shark attacks.

There are noticeable peaks in the distribution for individuals in their teens and twenties.

The distribution for male victims is higher across almost all age ranges compared to female victims, suggesting that males are more commonly involved in shark attacks.

### 3.1 Likelihood of Fatal Attacks by Age Group

 The age group '71-80' has the highest percentage of fatal attacks (28.57%), followed closely by '61-70' (25.53%). Younger age groups, particularly '11-20' and '21-30', also have a relatively high percentage of fatal attacks, exceeding 20%. The percentage of fatal attacks tends to decrease for age groups '41-60'. The '0-10' age group has a fatal attack percentage of 19.66%, which is notable since it involves very young individuals.

ACTIVITY ANALYSIS 

### 4) The activity that causes more shark attacks is surfing

![Image6](https://github.com/MairaMG/project--I/blob/main/images/7.Shark_Attacks_top_Activities.png)

People engaged in activities that involve close interaction with the water, such as surfing, swimming, and snorkeling, appear to be at a higher risk of shark attacks.
It's worth noting that the category "Other" includes activities that are unspecified or unknown, which could potentially be distributed among the other categories if more detailed information was available.

4.1) Are Types of Attacks and Activities correlated?

![Image7](https://github.com/MairaMG/project--I/blob/main/images/8.Shark_Attacks_by_type_activity.png)

The heatmap above visualizes the relationship between different activities and types of shark attacks, focusing on the top activities associated with shark incidents.

Unprovoked Attacks: The high number of unprovoked attacks in activities like surfing and swimming aligns with the common perception of these activities being more risky in terms of potential shark encounters.

Provoked Attacks: The presence of provoked attacks in fishing and diving activities suggests that interactions with sharks during these activities may sometimes lead to attacks.

Boating and Sailing: The relationship between boating incidents and sailing indicates that these incidents are more specific to activities involving boats.

This visualization helps to highlight the specific types of shark attacks that are more common with certain activities, providing valuable insights into the risks associated with different water-related activities.

# Conclusions

## 
THANK YOU!