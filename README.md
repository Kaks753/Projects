**Aviation Accident Analysis**

**Author: Muema Stephen** 

**Project Overview**

This project explores patterns in aviation accidents using a global dataset with 23,967 records.
The analysis focuses on frequency, severity, temporal trends, geographic distribution, operator involvement, and correlations.

The primary goal is to derive actionable insights and recommendations that can inform aircraft acquisition and operational safety strategies for a company planning to enter the aviation industry.

**Objectives**

>> To identify aircraft makes and models with the highest and lowest historical accident rates
>> To analyze temporal patterns in aviation accidents.  
>> To evaluate the geographical distribution of accidents and identify high-risk regions
>> To evaliate top operators by accident count
>> To examine relationships in the dataset.

**Dataset**

File: aviation-accident-data-2023-05-16.csv - https://www.kaggle.com/datasets/drealbash/aviation-accident-from-1919-2023

Cleaned rows: 18,111

Key columns: date, type, operator, fatalities, country, year, make, fatal_flag.

Added decade feature for long-term trend analysis.

**Key Findings**

A few aircraft makes and operators dominate accident counts, while most appear only rarely.

Most accidents are non-fatal; when fatalities occur, they are usually low but occasionally catastrophic.

Accident likelihood has decreased in modern decades; fatal outcomes are less common in recent years.

Geographic concentration shows some countries/operators carry higher risk.

Correlation nullifies the assumption of time-fatalities link; The near-zero correlation suggests that accident severity, measured in fatalities, does not follow a simple upward or downward trend over time. 

**Recommendations**

1. **Aircraft Selection:** Prioritize makes with lower accident counts when evaluating fleet acquisition.

2. **Operational Strategy:** Deprioritize high-frequency accident makes/models and operators unless offset by strong modern safety records.

3. **Geographic Focus:** Exercise caution in entering countries with consistently high incident rates.

4. **Temporal Trends:** Leverage improving safety standards by focusing on newer aircraft models with safer outcomes in recent decades.