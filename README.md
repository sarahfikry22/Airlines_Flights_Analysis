# Airline Delays Analysis Project

## Project Description
This project aims to analyze flight delay data to understand patterns and underlying causes of delays. Data from multiple airlines and destinations are analyzed to provide comprehensive insights into flight performance.

## Data
- Dataset was collected From Kaggle (https://www.kaggle.com/datasets/giovamata/airlinedelaycauses/data)
## The following data were analyzed:
- **Number of Flights**: 1.94 million flights.
- **Number of Destinations**: 304 destinations.
- **Number of Airlines**: 20 airlines.

## Data Model
The provided data model outlines the structure and relationships between various entities related to airline operations. Here's a summary of the key components:

1. **Carrier**:
    - Contains information about airlines, including codes (MIA Carrier Code, EOS Carrier Code).

2. **Airport**:
    - Stores details about airports, such as country code, location (latitude, longitude), and region name.

3. **Delayed Flights (Fact Table)**:
    - Tracks data related to flight delays, cancellations, and other operational metrics. Key fields include AirTime, DepDelay, CancellationCode, and Distance.

4. **Date**:
    - Manages date-related information, including day, month, year, and specific date keys for temporal analysis.

5. **Measures**:
    - Contains aggregated metrics such as average air time, average carrier delay, and average departure delay.

6. **Time**:
    - Defines time-related units like hour, minute, and specific time periods (e.g., Tuesday, ThursdayPeriod).

![image_alt](https://github.com/AhmedHussein486/Airlines_Flights_Analysis/blob/main/Data%20model%20.png)


## Key Components

### 1. Overview
This page provides a high-level overview of an **Airline Delays Analysis** project. It covers:

- **1.94 million flights** analyzed across **20 airlines** and **303 destinations**.
- Key regions include **North America**, **Europe**, **Asia**, **Africa**, and **Australia**.
- Main reasons for cancellations are **weather** (48%) and **carrier issues** (38.86%).

The summary highlights the scale of the analysis and the primary factors affecting flight cancellations.
![image_alt](https://github.com/AhmedHussein486/Airlines_Flights_Analysis/blob/main/Overview.png)



### 2. Airlines
This page provides a high-level overview of an **Airline Performance Dashboard**. It covers:

- **Aircraft and flight numbers** across various airlines.
- Key insights into **average delays**, **flight statistics**, and **diversions and cancellations**.

The summary highlights the operational efficiency and performance trends for different airlines.
![image_alt](https://github.com/AhmedHussein486/Airlines_Flights_Analysis/blob/main/Airlines.png)


### 3. Flights
This page provides a high-level overview of **Flight Performance Analysis**. It covers:

- **5367 aircraft** and **1.93 million completed arrivals**.
- **633 canceled** and **7754 diverted flights**.
- **Average air time:** 108.28 minutes.
- **Delayed arrivals:** 89.37%, **before-time arrivals:** 9.23%, **on-time arrivals:** 1.4%.
- **Flight Distribution** by destination and origin:
  - California, Texas, Illinois, Florida, Georgia: Significant numbers of flights.
- **Flights and Distance** analysis by day:
  - Consistent flight volume with average distances around 750 miles.
- **Airlines** covered include:
  - AirTran Airways, Alaska Airlines, Aloha, America West Airlines, American Airlines, American Eagle, ATA Airlines, Atlantic Coast Airlines, Atlantic Southeast Airlines, Comair, Continental Airlines, Delta Air Lines, ExpressJet Airlines, Frontier, Hawaiian Airlines.

The summary highlights key performance metrics and trends in flight data.
![image_alt](https://github.com/AhmedHussein486/Airlines_Flights_Analysis/blob/main/Flights.png)



### 4. Delay
This page provides key metrics and insights into flight performance, including aircraft and arrival statistics, cancellation and diversion data, average air time, and major destinations:


- **5367 aircraft** and **1.93 million arrivals**.
- **633 canceled** and **7754 diverted** flights.
- **Average air time:** 108.28 minutes.
- **89.37% delayed**, **1.4% on-time** arrivals.
- Major destinations: **California**, **Texas**, **Florida**.
- Analysis includes multiple airlines.

This should provide a quick and clear overview. Anything else you'd like to adjust?
![image_alt](https://github.com/AhmedHussein486/Airlines_Flights_Analysis/blob/main/Delay.png)



## Conclusions
This analysis provides valuable insights into airline performance and the causes of delays, which can help improve operational efficiency and customer experience.

