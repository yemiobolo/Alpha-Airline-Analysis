# Alpha-Airline-Analysis
This is an analysis for an Airline company
![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/PngItem_57732.png)

## Introduction
This is an analysis of an Airline called the Alpha Airline that I recently completed. The project involves data extraction, cleaning, analysis and visualization to derive actionable insights and answer crucial questions in order to help the airline make data driven decisions, using Microsoft Excel and Power BI. This project has helped to enhance my data analytics skills.

## Business Problem
1. How many flights use the A319 aircraft?
2. What is the most common type of aircraft across all flights?
3. Show the total revenue per aircraft type, assuming a 10% tax on all fares.
4. Where are we losing the most money?
5. Where are we most profitable?
6. How many flights are flown from O'Hare (ORD) to Los Angeles
International Airport (LAX)?
7. What was the most popular month to fly to Fort Lauderdale (FLL)?

## Data Extraction
The dataset folder is made up of 3 files:
1.	Airport file (.xlsx)
2.	Route file (.xlsx)
3.	Flight file (.xlsx)
4.	Aircraft file (.xlsx)

## Data Exploration and Transformations 
I performed some basic and advanced transformations on the dataset using both Excel functions and formulas. Some of these are;
--Date part extraction to extract/dissect the date into multiple data components using the *Text function* 

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/Flight%20text%20function.PNG)

--The multiplication formula to ascertain revenue after 10% tax deduction.

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/Flight%20multiply%20formula.PNG)

--The Vlookup to look for and merge specified values across sheets.

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/Flights%20Vlookup.PNG)

--Power BI Dax functions.

## Creating Dimensions Table
A date dimension contains all information about a certain date and makes analyzing data as efficiently and accurate as possible. The most commonly known date attributes are: day, week, month, quarter and year. Here I created four date dimension table;
-	Day of the week
-	Month of the year
-	Year
-	Month name

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/Flight%20text%20function.PNG)

## Loading Data to Power BI and Data Modeling
After I performed all the necessary data transformations, I loaded the data into Power BI for analysis and I also created relationships between the tables to enable data modeling.

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/flight%20data%20modeling.PNG)

## Analysis Dashboard

![](https://github.com/yemiobolo/Alpha-Airline-Analysis/blob/main/Flight%20folder/Flights%20Dashboard%203.PNG)

## Conclusions
From the analysis, out of 9,636 total flights recorded in both 2014 and 2015, Aircraft A319 had 3,879 total flights trudging behind Aircraft B737.
The most common type of aircraft across all flights is Aircraft B737.
The most profitable aircraft is Flight B737 having a total revenue of more than 235 million, which is almost the revenue of the remaining two aircraft combined.
699 flights were flown from O’Hare to Los Angeles
International Airport.
7. the most popular moth to fly to Fort Lauderdale (FLL) is June with 26 flights closely followed by August with the total number of 25 flights.






