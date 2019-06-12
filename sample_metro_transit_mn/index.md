---
title: Sample Data: Metro Transit Bus Incident Data
---

# Metro Transit Bus Incident Data

### *Matthew.Broughton@metrotransit.org*

### *2018-06-12*

### Reformatted from the original HTML file

# Introduction

This document provides metadata to accompany data provided to the TRB APO10 Performance Measure Contest.

Data were requested in June, 2018.

# Data Sources

## Bus Incidents

Metro Transit operators submit a “Special Situation Report” or SSR for any unusual incident, and all accidents, while in operation. The SSRs are reviewed and coded by safety specialists and used for a wide range of purposes. An SSR does not necessarily indicate there was an accident, or suggest there would be a police report. A short narrative is included in the SSR, while more detailed descriptions and records may be kept in personnel, police, or safety records. These records are not included in the data provided here.

For some incidents, video from cameras inside the bus is requested and reviewed by Metro Transit safety personnel. The video can be used to update the exact time of the incident, the narrative, and the exact location of the incident. When this is done, data are entered into additional fields described below.

## Metadata

The provided dataset is for SSR records with an exact time given by video review from 2016-02-03 and 2018-05-08.

There are 1,785 rows in the dataset with the following columns:

| Column_name | Column_type | Column_desc|
|---|---|---|
| Date | character | Date of incident|
| TimeVideo | character | Updated time of incident, following video review by safety specialist, in HH:MM:SS|
| updateLat | numeric | Latitude in Decimal Degrees of the incident location as updated following video review by safety specialist. Should reflect the actual location of the incident.|
| updateLon | numeric | Longitude in Decimal Degrees of the SSR incident location as updated following video review by safety specialist. Should reflect the actual location of the incident.|
| Description | character | Type of incident|
| Route | integer | Route number vehicle was operating, if applicable|
| direction | character | Description of route direction, if known|
| Vehicle | character | Property tag of vehicle involved in incident|
| Passenger_Count | integer | Number of passengers on the bus at the time of the incident, if known|

## Sample Data

|Date | TimeVideo | updateLat | updateLon | Description | Route | direction | Vehicle | Passenger_Count|
|--- | --- | --- | --- | --- | --- | --- | --- | --- |
|2017-01-28 | 19:24:00 | 45.09329 | -93.37953 | Passenger falls out of mobility device | 724 | NA | 1535 | NA|
|2016-08-19 | 20:14:00 | 45.01323 | -93.25228 | With fixed objects | 17 | NA | 7223 | 0|
|2016-08-19 | 20:14:00 | 45.01329 | -93.25671 | With fixed objects | 17 | NA | 7223 | 0|
|2017-09-11 | 20:19:00 | 44.94869 | -93.25260 | Falls alighting - front door | 14 | NA | 1438 | NA|
|2017-04-20 | 17:29:00 | 45.07916 | -93.33573 | Incidents not otherwise classified | 781 | NA | 60033 | NA|
|2017-01-11 | 16:23:00 | 44.99191 | -93.29477 | Falls, bumps, etc. - bus starting | 5 | NA | 1656 | NA|