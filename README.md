# Electric Vehicle Data Analysis
![Screenshot (920)](https://github.com/user-attachments/assets/c301a5ec-1efd-41d1-a297-9e627748a5f6)


### Background and Overview

### Objective
The primary objective of this project is to analyze the sales of the Electric Vehicles sold in the United States and deliver key insights

### Data Source and Overview
Analytics Data: The data set used for analysis is the Electric_vehicle_cleaned_data.csv

### Tools
Utilized Python for Data cleaning and Tableau for Data Visualization

### Data Cleaning
The following steps were performed in the Data Cleaning phase using Python:

### Executive Summary of the Data Analysis

#### Top 10 Vehicles by Make
![Screenshot (921)](https://github.com/user-attachments/assets/4566c229-f7d4-4b10-b7dd-3bd7175a5a41)

•	The bar chart visualizes the distribution of electric vehicle manufacturers, with each bar representing the total number of vehicles attributed to a particular make. The length of the bar corresponds to the number of vehicles, providing a clear comparative overview. The key insights are as follows:

•	Top 10 Vehicle Manufacturers:
The top 10 manufacturers are listed in descending order based on the total number of vehicles. This ranking highlights the leaders in the electric vehicle market.

•	Color Encoding:
Each manufacturer is represented by varying shades of green. Darker shades indicate a higher vehicle count, making it easy to identify the top contributors at a glance.

•	Tesla's Market Dominance:
•	Tesla leads the market significantly, with a total of 68,943 vehicles, showcasing its dominant market presence compared to other manufacturers.

•	Strong Contenders:
Nissan and Chevrolet follow as strong contenders, with 13,497 and 12,025 vehicles, respectively. While they maintain a solid presence, their numbers are significantly lower than Tesla's.

•	Mid-Tier Manufacturers:
Ford (7,601), BMW (6,439), and Kia (6,198) represent the mid-tier manufacturers, contributing a moderate number of vehicles to the market.

•	Smaller Market Players:
Toyota, Volkswagen, Volvo, and Jeep complete the top 10, each with fewer than 6,000 vehicles. These manufacturers have a relatively small share of the electric vehicle market compared to the leading companies.

Key Insights:

•	Tesla's Market Leadership: Tesla's overwhelming lead indicates its stronghold on the electric vehicle market, vastly surpassing other manufacturers.

•	Market Concentration: The combined presence of Tesla, Nissan, and Chevrolet constitutes a significant portion of the market, while other manufacturers contribute much smaller volumes.

•	Market Dynamics: The stark difference between the top three manufacturers and the rest of the top 10 highlights a highly concentrated market with Tesla at the forefront

#### Total Vehicles by CAFV Eligibility
![Screenshot (923)](https://github.com/user-attachments/assets/baaf8cc8-f569-4263-a790-b17cb9581df6)

•	The analysis focuses on the total number of vehicles classified under different categories of CAFV (Clean Alternative Fuel Vehicle) eligibility. Two specific subsets are highlighted, each representing a distinct category based on battery range and eligibility status:

•	Top Label (60,613 Vehicles):
This subset represents 60,613 vehicles for which CAFV eligibility could not be determined due to missing data on battery range. The label indicates: “Eligibility unknown as battery range has not been researched.” These vehicles might require further investigation to establish their eligibility status, highlighting a potential data gap in battery range information.

•	Bottom Label (14,287 Vehicles):
This subset comprises 14,287 vehicles categorized as “Not eligible due to low battery range.” These vehicles do not meet the minimum battery range criteria required for CAFV eligibility.

•	Average Line (43,608.33 Vehicles):
A dotted horizontal line marks the average number of vehicles (43,608.33) across all categories. This average serves as a reference point to compare different eligibility categories. The positioning of the average closer to the ineligible subset (14,287 vehicles) suggests that the substantial number of vehicles with unknown eligibility status (60,613 vehicles) skews the overall average upwards.

Observations:

•	Significant Proportion of Vehicles with Unknown Eligibility:
The largest subset comprises vehicles whose eligibility status remains undetermined due to insufficient data on battery range. This indicates a need for enhanced data collection and further research to accurately classify these vehicles.

•	Smaller Proportion of Ineligible Vehicles:
A comparatively smaller subset of 14,287 vehicles is ineligible due to low battery range. These vehicles fall below the required threshold for CAFV eligibility, highlighting a specific area for potential improvement in battery technology.

•	Implications of the Average Positioning:
The average line's proximity to the ineligible vehicles category suggests that the unknown eligibility group has a significant impact on the overall distribution. Resolving the unknown eligibility data could potentially alter the overall pattern and provide a clearer understanding of the market’s eligibility landscape.

#### Total Vehicles Sold by Year
![Screenshot (925)](https://github.com/user-attachments/assets/b5b12728-e28f-4339-ad9c-e96010ace3bb)

The area chart illustrates the total vehicle sales over time, with the green shaded area representing sales volume across different years. The expansion and contraction of the area correspond to growth and fluctuations in sales numbers. Key data points are marked for each year, providing a visual overview of sales trends from 2011 to 2024.

•	Steady Growth in Sales (2011–2018):Vehicle sales exhibited a steady increase, starting from 786 vehicles in 2011 and reaching a peak of 12,596 vehicles in 2018. This upward trend indicates robust market growth and increased consumer demand during this period.

•	Sales Decline in 2019:
After the 2018 peak, sales declined to 9,263 vehicles in 2019. This downturn could be attributed to market saturation, economic factors, or challenges within the industry.

•	Recovery and Peak in 2023:
The market rebounded with a significant rise to 30,366 vehicles in 2023, the highest figure in the dataset. This resurgence may be due to factors such as the launch of new models, increased consumer interest, or favorable market conditions.

•	Sharp Drop in 2024:
A dramatic decline to just 305 vehicles in 2024 is observed, suggesting a possible data issue (incomplete reporting for 2024) or a substantial market disruption affecting vehicle sales.

Key Insights:

•	Rapid Market Expansion:
The strong growth from 2011 to 2023 reflects a rapid expansion of the vehicle market, culminating in the highest sales figures in 2023.

•	Market Volatility:
The decline in 2019, followed by the sharp drop in 2024, highlights volatility in the market. These fluctuations could be driven by economic conditions, shifts in consumer preferences, or external disruptions.

•	Potential Data Gap in 2024:
The steep decrease in sales in 2024 suggests either incomplete data or significant market upheaval. Further investigation is needed to confirm whether this drop is due to missing data or an actual decline in vehicle sales.

#### Total Vehicles by State

#### City wise Total PHEV

### Insights and Recommendations






