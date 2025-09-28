# India Domestic Flights Analytics-2019

## Overview:
This project analyzes a comprehensive dataset of 10,683 domestic flights in India from 2019, encompassing key attributes such as airline, date of journey, source, destination, route, departure and arrival times, duration, total stops, additional information, and ticket prices. 

## Objectives:
The objective is to uncover actionable insights to address specific questions about flight distributions, pricing trends, and travel patterns, while also exploring additional trends to enhance understanding. Key analyses include the distribution of flights by stoppages, identification of the most expensive and cheapest flights, price variations by source city, flight frequency by day and month, and the impact of additional services on pricing.  A notable finding is that non-stop flights are often among the cheapest, challenging common assumptions about flight pricing.

## About the Data:
The dataset contains domestic flight ticket records from India (2019).
Each row represents details of a single flight ticket.
- Rows: 10799
- Columns: 11
- File Used: Data_Train.xlsx

## Data Information:
Key columns:
- Airline – Name of the airline operating the flight
- Date_of_Journey – Travel date 
- Source – Departure city
- Destination – Arrival city
- Route – Route taken by the flight
- Dep_Time – Scheduled departure time
- Arrival_Time – Scheduled arrival time
- Duration – Total journey time (hours & minutes)
- Total_Stops – Number of stoppages in the journey
**Categories include:**
  - non-stop
  - 1 stop
  - 2 stops
  - 3 stops
  - 4 stops
- Additional_Info – Miscellaneous details such as in-flight meals, baggage, no info, etc.
- Price – Ticket price

## Cleaning Steps Performed:
- Converted Date_of_Journey to proper datetime format
- Extracted Day and Month from journey date
- Converted Duration into total hours and minutes
- Standardized values in Total_Stops column
- Cleaned and normalized Additional_Info
- Checked and handled missing/irrelevant values

## Impurities Removed:
- Inconsistent date/time formats fixed
- Duration column standardized into numeric values

## Insights:
- people generally prefer flights with fewer stops.
- Delhi and Mumbai showed the highest flight frequencies
- Jet Airways Business class tickets were among the most expensive
- Ticket prices varied significantly by source city
- Additional services had a notable impact on pricing
- Seasonal/monthly flight frequency patterns were observed
