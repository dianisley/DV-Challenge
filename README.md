<img width="260" alt="Screenshot 2024-07-13 233636" src="https://github.com/user-attachments/assets/1d0480ef-3db8-4928-a4a2-d05ea875800b">

# HotelFlix Data Visualization Challenge

This repository contains the solutions to the Data Visualization Challenge presented by Bayer & Google for HotelFlix, a leading company in data-driven boutique hotel experiences. The challenge is divided into four parts, each addressing different business needs of HotelFlix. The goal is to leverage data analytics to enhance their market position and operational efficiency.


## Table of Contents

- [Introduction](##introduction)
- [Understanding the Seasonality of the Bookings](##understanding-the-seasonality-of-bookings)
- [Creating the Shape of Future Hotel Packages](##creating-the-shape-of-future-hotel-packages)
- [Comprehending the Cancellation Foundations](##comprehending-the-cancellation-foundations)
- [Preparing the IT Systems for the Demand](##preparing-the-it-systems-for-the-demand)
- [Conclusions](##conclusions)
- [Contact](##contact)

## :scroll: Introduction

HotelFlix is striving to improve its understanding of booking patterns, optimize pricing strategies, create attractive packages, and establish effective cancellation policies. This project uses historical booking data to derive insights and propose actionable strategies across four main areas:

- Understanding booking seasonality.
- Designing hotel stay packages.
- Developing a cancellation policy.
- Preparing IT systems for future demand.
  
## :one: Understanding the Seasonality of the Bookings

Objective: Analyze the seasonality in bookings to propose a dynamic pricing model.

Approach:
- Visualized the number of bookings per day and month using line plots.
- Identified high and low booking seasons.
- Proposed a tiered pricing model with three categories: Peak, Shoulder, and Off-Peak periods.

Tools & Libraries:
- Python, Pandas, Matplotlib, Seaborn.
- Power BI as Visualization Tool

<img width="1600" alt="Pricing Strategy" src="https://github.com/user-attachments/assets/80fce01b-4db1-4dbf-bb0b-a159d9032931">

Insights:
- Peak season occurs during summer and holiday periods.
- Shoulder seasons include spring and autumn.
- Off-Peak season is typically in winter, excluding the holiday period.
## :two: Creating the Shape of Future Hotel Packages

Objective: Determine typical stay durations to design attractive hotel packages.

Approach:
- Analyzed the distribution of stay durations using bar plots.
- Suggested multiple stay packages based on the most common stay durations.

Tools & Libraries:
- Python, Pandas, Matplotlib.
- Power BI as Visualization Tool

<img width="1600" alt="image" src="https://github.com/user-attachments/assets/3ec95563-100d-449a-8501-6e1c954be1f3">

Insights:
- Common stay durations include weekend getaways (2-3 days) and week-long vacations (7 days).
- Proposed packages: 2-day, 3-day, 7-day, and extended stay options (10+ days).
  
## :three: Comprehending the Cancellation Foundations

Objective: Develop a cancellation policy to reduce financial loss from cancellations.

Approach:
- Analyzed cancellation patterns based on lead time.
- Created a tiered penalty system for cancellations.

Tools & Libraries:
- Python, Pandas, Matplotlib.
- Power BI as Visualization Tool
  
<img width="1600" alt="Cancellation Strategy" src="https://github.com/user-attachments/assets/8f2b32bd-f464-402c-942b-d0ecd1a87876">

Insights:
- Higher cancellation rates were observed closer to the arrival date.
- Proposed penalty tiers:
    - 0-7 days: 90% penalty.
    - 8-30 days: 50% penalty.
    - 31-90 days: 25% penalty.
    - 91+ days: 10% penalty.
      
## :four: Preparing the IT Systems for the Demand

Objective: Forecast future booking demand to ensure IT systems can handle peak loads.

Approach:
- Calculated the number of days between booking and arrival date to identify peak booking weeks.
- Used SARIMA model to forecast future demand.
  
<img width="901" alt="Forecast" src="https://github.com/user-attachments/assets/4428f4b8-3b8d-4963-a786-64e2f4ab6567">

Tools & Libraries:
- Python, Pandas, Matplotlib, Statsmodels.
- Power BI as Visualization Tool


Insights:
- Forecasted peak demand weeks based on historical data.
- Recommended IT system enhancements to handle forecasted load.
  
## :information_source: Conclusions

This project provided actionable insights into booking patterns, stay durations, cancellation behaviors, and future demand forecasting. The proposed strategies aim to optimize HotelFlix's operations and improve customer satisfaction.

Link to Power BI Report: [HotelFix Data-Perfected Stays](https://app.powerbi.com/view?r=eyJrIjoiNDFhOGI2YjAtMmQ0ZS00YjI1LWJiNDMtZTk0OWE4ZDM4MGQzIiwidCI6ImUwMDI3MzIwLWE2YjYtNGM5ZC1iNzBmLTM3ZTdmNzc5ZDBiMiJ9)

## :penguin: Contacts

- Author : Diana Fernandez
- Email : dianaf@alumni.ie.edu
- Github : https://github.com/dianisley/DV-Challenge.git


