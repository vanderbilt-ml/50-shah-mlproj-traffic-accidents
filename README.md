# 50-shah-mlproj-traffic-accidents
Use of machine learning to analyze historical traffic accidents data.

## Background

This is dataset of traffic accidents reported from 2010 to present. The data is exported daily using automated scripts and is subject to change during an investigation as more information becomes available.

## Project Description

Each record is a reported traffic accident. Check the below descriptions for more detailed information.

### **Data Dictionary**

Feature	|	Description	|	Type
-------------	|	-------------	|	-------------
Accident Number	|	MNPD incident number for the crash	|	Plain Text
Date and Time	|	Date and time of the accident	|	Date & Time
Number of Motor Vehicles	|	Number of vehicles involved in the accident	|	Number
Number of Injuries	|	Number of people with injuries as a result of the accident	|	Number
Number of Fatalities	|	Number of fatalities as a result of the accident	|	Number
Property Damage	|	Indicates if there was property damage as a result of the accident	|	Checkbox
Hit and Run	|	Indicates if the accident was a hit and run	|	Checkbox
Reporting Officer	|	ID number of the officer responding to the accident	|	Plain Text
Collision Type Code	|	System code for the type of collision	|	Number
Collision Type Description	|	Full text description of the collision type	|	Plain Text
Weather Code	|	System code for the weather conditions at the time of the accident	|	Number
Weather Description	|	Full text description of the weather conditions	|	Plain Text
Illumination Code	|	System code for type of lighting at the time of the accident	|	Number
Illumination Description	|	Full text description of the lighting conditions	|	Plain Text
Harmful Code	|	System code indicating harmful objects or conditions present in the accident	|	Plain Text
Harmful Description	|	Full text description of the harmful objects or conditions	|	Plain Text
Street Address	|	Street address at which the accident occurred	|	Plain Text
City	|	City in which the accident occurred	|	Plain Text
State	|	State in which the accident occurred	|	Plain Text
ZIP	|	ZIP Code in which the accident occurred	|	Number
RPA	|	MNPD reporting zone in which the accident occurred	|	Number
Precinct	|	Assigned MNPD precinct in which the accident occurred	|	Plain Text
Latitude	|	Approximate latitude where the accident occurred	|	Number
Longitude	|	Approximate longitude where the accident occurred	|	Number
Mapped Location	|	Combined latitude and longitude for the accident for mapping purposes	|	Point

## Performance metrics

If successfull, the project will break down accident frequency by day of week and hour of day. One can also identify, when do accidents occur most frequently.
