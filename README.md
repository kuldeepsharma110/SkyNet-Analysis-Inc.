# SkyNet-Analysis-Inc.
Sky Analytics: Navigating the Complexities of Airline and Airport Operations

![image](https://github.com/user-attachments/assets/16e3e1c9-75d8-429d-8365-c8b37d8d761d)


## Company Overview
SkyNet Analysis Inc. is a leading consultancy firm specializing in aviation analytics. With the aviation industry's rapid expansion and the increasing complexity of global air travel, SkyNet plays a critical role in providing data-driven insights to airlines, airports, and regulatory bodies. The company has access to extensive datasets that cover a wide range of information, including flight schedules, delays, airline operations, and airport traffic details. These datasets offer a unique opportunity to explore and understand the multifaceted nature of the aviation industry, from operational efficiency and customer satisfaction to logistical challenges and environmental impact.

## Objective
The primary objective of this case study, titled "Sky Analytics: Navigating the Complexities of Airline and Airport Operations," is to deeply analyze and interpret the extensive datasets encompassing flights, airlines, and airports - namely "flights.csv", "airlines.csv", and "airports.csv". The analysis aims to uncover critical insights into flight operations, delay patterns, airline efficiency, and airport traffic dynamics. By exploring these datasets, the study seeks to identify key factors influencing operational efficiency, understand the intricacies of flight scheduling and delays, and evaluate the performance metrics of airlines and airports. The ultimate goal is to provide strategic recommendations to enhance operational effectiveness, improve customer experiences in air travel, and contribute to the overall advancement of the aviation industry's standards and practices.

## Datasets
**Flights** dataset contains detailed flight information, including timings, delays, and other flight-specific data.

- **YEAR, MONTH, DAY, DAY_OF_WEEK**: Date and day information for the flight.
- **AIRLINE**: Airline identifier.
- **FLIGHT_NUMBER**: Flight number.
- **TAIL_NUMBER**: Aircraft tail number.
- **ORIGIN_AIRPORT, DESTINATION_AIRPORT**: Airport codes for origin and destination.
- **SCHEDULED_DEPARTURE, DEPARTURE_TIME**: Scheduled and actual departure times.
- **DEPARTURE_DELAY**: Delay in departure (minutes).
- **TAXI_OUT**: The time duration between departure from the gate and wheels off.
- **WHEELS_OFF, WHEELS_ON**: Time when wheels were off/on the ground.
- **SCHEDULED_TIME**: Scheduled duration of the flight.
- **ELAPSED_TIME**: Actual time taken for the flight.
- **AIR_TIME**: Time in the air.
- **DISTANCE**: Distance covered by the flight.
- **TAXI_IN**: The time duration from wheels on to arrival at the gate.
- **SCHEDULED_ARRIVAL, ARRIVAL_TIME**: Scheduled and actual arrival times.
- **ARRIVAL_DELAY**: Delay in arrival (minutes).
- **DIVERTED, CANCELLED**: Indicators for diverted or cancelled flights.
- **CANCELLATION_REASON**: Reason for cancellation (if any).
- **AIR_SYSTEM_DELAY, SECURITY_DELAY, AIRLINE_DELAY, LATE_AIRCRAFT_DELAY, WEATHER_DELAY**: Different types of delays (minutes).

**Airlines** dataset provides information about various airlines.

- **IATA_CODE**: Unique airline code.
- **AIRLINE**: Full name of the airline.

**Airports** dataset contains information about various airports.

- **IATA_CODE**: Unique airport code.
- **AIRPORT**: Full name of the airport.
- **CITY**: City where the airport is located.
- **STATE**: State where the airport is located.
- **COUNTRY**: Country where the airport is located.
- **LATITUDE, LONGITUDE**: Geographic coordinates of the airport.

## Information Gained

* The top 3 airlines with the highest average delays.

   ![image](https://github.com/user-attachments/assets/bb9c60b6-f4c0-4042-9985-a61d2e96e88b)

* The top 5 busiest airports based on the number of incoming and outgoing flights.

  ![image](https://github.com/user-attachments/assets/929561d6-966a-4b41-b3a8-8c8943760f5f)

* Airline that has the highest cancellation rate, and the most common reasons for cancellations.

   ![image](https://github.com/user-attachments/assets/87f5a861-21ec-4a96-b913-2830fe360f7b)

* Months more prone to delays or cancellations.

  ![image](https://github.com/user-attachments/assets/1cb4da9f-1ec0-4ea5-b465-038025d5b84d)

* Investigate if there's a correlation between the distance of the flight and the length of delays.

  ![image](https://github.com/user-attachments/assets/bf82c3ac-14eb-4ff3-949b-a7205f8250b0)

  **Most of the delay are between 0 to 30 minutes when distance is between 0 to 2700.**

* Airline wise percentage of flights that are not delayed.

  ![image](https://github.com/user-attachments/assets/9fba66fb-fa3e-496e-bc48-fcca1c35c205)

* Assess how flight operations (delays, cancellations) vary by the day of the week.

   ![image](https://github.com/user-attachments/assets/9da747e0-531e-4a15-a4bd-92a0082ade3c)

* Analysis of Airport Connectivity

   ![image](https://github.com/user-attachments/assets/843d5caa-fb69-452d-966f-0fd126855933)

  **Most number of destinations are served by ATL**

* Compare the scheduled flight duration versus the actual flight duration. Which airlines have the most and least deviation?

   ![image](https://github.com/user-attachments/assets/9a558d50-d374-4267-a9b9-12de2ad95f6e)
  
   **F9 have least deviation and UA have most deviation.**






