# Kerala-Floods

## Overview

#### Kerala-Floods-Analysis using python and Power BI:

The Kerala floods, particularly the catastrophic event in 2018, highlighted the importance of understanding environmental and human factors contributing to such disasters. The analysis of Kerala floods involves examining rainfall patterns, river basin dynamics, and land-use changes over time. Key factors include the unprecedented monsoon rainfall, which exceeded normal levels by 42%, and the mismanagement of dam reservoirs, leading to widespread flooding.

Data analytics plays a crucial role in flood prediction and management by using historical data, satellite imagery, and real-time monitoring to forecast flood events, assess risk areas, and plan effective response strategies. The integration of these insights into disaster management frameworks can significantly mitigate the impact of future floods and enhance resilience in vulnerable regions like Kerala.This is data set containing rainfall per month from 1901 to 2018. 


## Project Components

Data Souce : CSV file
Notebook : Jupyter Notebook
Libraries used for Data cleaning, Preprocessing, EDA and Machine leraing model : Pandas, Numpy, Seaborn, Matplotlib, Scikit Learn
Dashboard : Power BI


## Key Findings

The logistic regression model shows strong performance in predicting floods based on annual rainfall data, with an overall accuracy of 90%. The model is particularly effective at identifying actual flood events (high recall for Class 1), though it occasionally misclassifies "No Floods" as "Floods" (7 instances).

The balanced performance across precision, recall, and F1 score suggests that the model is both reliable and accurate, making it a useful tool for predicting flood occurrences based on the given rainfall data. However, there is a small trade-off in that the model is more cautious, resulting in a few false alarms where it predicts floods that don't occur (false positives). 
Other findings are:-

1. Flood Ocuured 60 times in Kerala along the years.
2. Maximum annual rainfall occured is 4473.0 and maximum annual rainfall which caused flood is also 4473.0 which is in the year 2018.
3. Flood occured when annual rainfall is above 2900 and below 2900 no flood occured.
4. More relation is seen in the months of June and July(Monsoon Season) when comparing annual rainfall and flood occurrences.
5. Winter season shows less relation to the annual rainfall and floods. Therefore, the chance of flooding is less during this season.
6. Percentage of occuring flood in June, if the rainfaill is greater than 500mm is 58% and Percentage of occuring flood in July, if the rainfaill is greater than 500mm is 59%.
