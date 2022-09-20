# DRAFT PROPOSAL

## Project Title: LOS ANGELES CRIME DATA ANALYSIS

Name: Naga Chandrika Bhamidi
    
Date: 09/18/2022

## Overview:

Los Angeles is located in southern California and is the second most populous city in the United States (second only to New York), as well as the heart of the film and television industries. According to the International Association of Crime Analysts (IACA), crime analysis is defined as a profession and process in which a set of quantitative and qualitative techniques are used to analyze data valuable to police agencies and their communities. It includes the analysis of crime and criminals, crime victims, disorder, quality of life issues, traffic issues, and internal police operations, and its results support criminal investigation and prosecution, patrol activities, crime prevention and reduction strategies, problem solving, and the evaluation of police efforts.

This data set contains the "Los Angeles crime data history." A crime is an unlawful conduct, and we have heard about many sorts of crimes that have occurred in various locations. In this section, I will classify the Los Angeles crime report, which covers all sorts of crimes that are typed on paper, and therefore there may be some inaccuracies within the data. We have data from the year 2020 until the present.

## Dataset:

#### Data Source: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

This collection includes all legitimate felony, misdemeanor, and infraction offenses reported to the Los Angeles Police Department. The data set consist of 564162 rows and 28 columns which is collected from 2020 to present. Because the data set contains the most recent crime data, we can clearly analyze the reasons and links between the crimes by taking the victims' age, type of crime, and all the variables in the data set, which helps people to have a clear idea of how to protect or overcome the crimes and also police departments to prevent more crimes from occurring.

## Variables in dataset:


•	DR_NO - Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.
    
•	DATE OCC - Date of crime occurrence (YYYY-MM-DD)

•	AREA - The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21.

•	AREA NAME - The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for.

•	Rpt Dist No - Code that represents a sub-area within a Geographic Area.

•	Crm Cd - Indicates the crime committed.

•	Crm Cd Desc - Defines the Crime Code provided.

•	Vict Age - Indicates the age of the victim.

•	Vict Sex - F: Female M: Male X: Unknown
            
•	Premis Cd - The type of structure, vehicle, or location where the crime took place.

•	Premis Desc - Defines the Premise Code provided.

•	Weapon Used Cd - The type of weapon used in the crime.

•	Weapon Desc - Defines the Weapon Used Code provided.

•	LOCATION - Street address of crime incident rounded to the nearest hundred block to maintain anonymity.

•	LAT - Latitude Coordinate.

•	LON - Longitude Coordinate

•	Vict Descent - Descent Code: A - Other Asian B - Black C - Chinese D - Cambodian F - Filipino G - Guamanian H - Hispanic/Latin/Mexican I - American Indian/Alaskan Native J - Japanese K - Korean L - Laotian O - Other P - Pacific Islander S - Samoan U - Hawaiian V - Vietnamese W - White X - Unknown Z - Asian Indian 


## Techniques and Models:

• Decision Tree Classifier

• Random forest

• Support vector machine

• Decision tree

• K-nearest neighbor

• Logistic Regression


## Outcome:

I would like to build the models using a pipeline and explain how ML models can be used to predict the exact location and weapons used against the victim in a crime. Using EDA, I want to find out and plot the top crime zones, which are the main areas where crimes have occurred, types of crimes, suspects' ages, suspects' gender, and the locations where the crimes are commonly committed.

## References:

https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8 https://medium.com/analytics-vidhya/los-angeles-crime-data-analysis-using-pandas-a68780d80a83
https://bja.ojp.gov/sites/g/files/xyckuh186/files/media/document/OverviewofCrimeAnalysis.pdf

