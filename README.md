# Data606_NagaChandrika


## LOS-ANGELES CRIME ANALYSIS


Data Source: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

Youtube Link: https://youtu.be/ie_U4iFX1Eg

Ppt Link: https://github.com/DATA-606-FALL-2022/Data606_Naga_Chandrika/blob/main/DATA606-Final%20ppt.pptx




![Los-Angeles](https://user-images.githubusercontent.com/89950108/208333693-d3e02449-70aa-4c77-afff-f164a5429164.png)

### Abstract

Crime is one the most common social problems in the country impacting public welfare, children development, and adult socio-economic status. Crime analysis and prevention is a systematic approach for identifying and analyzing trends. With the advent of modern technology, crime data analysts can help Law Enforcement agencies to prevent crime incidents. I would like to represent an extensive proposal about the varying crimes in the city of Los Angeles. The purpose of this data analysis is to be aware of the patterns in criminal manners in order to anticipate crime activity and how can it be prevented. Predict the analytics for investigating various crime trends and patterns. The main objective of this project is to provide location based, and crime-type based rate and count, which may help the society to minimize the crime.


### Introduction

Los Angeles is located in southern California and is the second most populous city in the United States (second only to New York), as well as the heart of the film and television industries. According to the International Association of Crime Analysts (IACA), crime analysis is defined as a profession and process in which a set of quantitative and qualitative techniques are used to analyze data valuable to police agencies and their communities. It includes the analysis of crime and criminals, crime victims, disorder, quality of life issues, traffic issues, and internal police operations, and its results support criminal investigation and prosecution, patrol activities, crime prevention and reduction strategies, problem solving, and the evaluation of police efforts.

This data set contains the "Los Angeles crime data history." A crime is an unlawful conduct, and we have heard about many sorts of crimes that have occurred in various locations. In this section, I will classify the Los Angeles crime report, which covers all sorts of crimes that are typed on paper, and therefore there may be some inaccuracies within the data. We have data from the year 2020 until the present.


### About Dataset:

This collection includes all legitimate felony, misdemeanor, and infraction offenses reported to the Los Angeles Police Department. The data set consist of 564162 rows and 28 columns which is collected from 2020 to present. Because the data set contains the most recent crime data, we can clearly analyze the reasons and links between the crimes by taking the victims' age, type of crime, and all the variables in the data set, which helps people to have a clear idea of how to protect or overcome the crimes and also police departments to prevent more crimes from occurring.

### Significance of the project

To determine the top crime zones, which are the primary places where crimes have happened from 2020 to the present, the sorts of crimes, the most common age of victims, the gender of suspects, and the locations where the crimes are usually committed. To help people understand the precautions better, I'd want to create models that show the specific weapons that are being used as well as the location where people must be more cautious.

### Type of Issue

Machine Learning Classification model (To predict type of Weapon and Location)

### Features in dataset:

DR_NO - Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.

• DATE OCC - Date of crime occurrence (YYYY-MM-DD)

• AREA - The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21.

• AREA NAME - The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for.

• Rpt Dist No - Code that represents a sub-area within a Geographic Area.

• Crm Cd - Indicates the crime committed.

• Crm Cd Desc - Defines the Crime Code provided.

• Vict Age - Indicates the age of the victim.

• Vict Sex - F: Female M: Male X: Unknown

• Premis Cd - The type of structure, vehicle, or location where the crime took place.

• Premis Desc - Defines the Premise Code provided.

• Weapon Used Cd - The type of weapon used in the crime.

• Weapon Desc - Defines the Weapon Used Code provided.

• LOCATION - Street address of crime incident rounded to the nearest hundred block to maintain anonymity.

• LAT - Latitude Coordinate.

• LON - Longitude Coordinate

• Vict Descent - Descent Code: A - Other Asian B - Black C - Chinese D - Cambodian F - Filipino G - Guamanian H - Hispanic/Latin/Mexican I - American Indian/Alaskan Native J - Japanese K - Korean L - Laotian O - Other P - Pacific Islander S - Samoan U - Hawaiian V - Vietnamese W - White X - Unknown Z - Asian Indian

### Target Variable

Weapons Description is my target variable. Coming to the question I woul dlike to know different types of weapons used in the crime from 2020 to present.

### Exploratory data and complete Analysis

• Extracted the data in the form of csv file and converted it into pandas dataframe.

• Learned and analysed more about the data by using functions like info, describe, shape etc.

• Since the raw has null and unknow values cleansed the data and stored it in the new CSV file

• To know more about the data done different visualization.

• Got some insights so performed ml models using algorithms

• Identified the most accurate and important classification model.

### Techniques and models

#### Pre-Processing Data:
Data preprocessing is a step in the data mining and data analysis process that takes raw data and transforms it into a format that can be understood and analyzed by computers and machine learning. Raw, real-world data in the form of text, images, video, etc., is messy. Not only may it contain errors and inconsistencies, but it is often incomplete, and doesn’t have a regular, uniform design. Steps for pre-Processing the data are Data quality assessment, Data cleaning, Data transformation and Data reduction

#### Exploratory data analysis (EDA):
Exploratory data analysis (EDA) is a term for certain kinds of initial analysis and findings done with data sets, usually early on in an analytical process. Some experts describe it as “taking a peek” at the data to understand more about what it represents and how to apply it. Exploratory data analysis is often a precursor to other kinds of work with statistics and data

#### Logistic Regression
It is a supervised learning classification technique that forecasts the likelihood of a target variable. There will only be a choice between two classes. Data can be coded as either one or yes, representing success, or as 0 or no, representing failure. The dependent variable can be predicted most effectively using logistic regression. When the forecast is categorical, such as true or false, yes or no, or a 0 or 1, you can use it. A logistic regression technique can be used to determine whether or not an email is a spam.

#### Decision Tree
A decision tree is an example of supervised learning. Although it can solve regression and classification problems, it excels in classification problems. Similar to a flow chart, it divides data points into two similar groups at a time, starting with the "tree trunk" and moving through the "branches" and "leaves" until the categories are more closely related to one another.

#### Random Forest Algorithm
The random forest algorithm is an extension of the Decision Tree algorithm where you first create a number of decision trees using training data and then fit your new data into one of the created ‘tree’ as a ‘random forest’. It averages the data to connect it to the nearest tree data based on the data scale. These models are great for improving the decision tree’s problem of forcing data points unnecessarily within a category.

#### K-Nearest Neighbors
t calculates the likelihood that a data point will join the groups based on which group the data points closest to it are a part of. When using k-NN for classification, you determine how to classify the data according to its nearest neighbor.

### Best machnie learning model

The classification report which is generated by using the Machine Learning models says that the Logistic Regression, Decision Tree and KNN Model has almost the same accuracy value i.e around 70%. So all the three models are good for this data. Random Forest is also a good model but a bit less when we compared with the rest three models.

### Conclusion

Male victims are more than female victims.
Battery- Simple Assault is the highest with nearly 50k crimes registered.
Streets are becoming the most dangerous place since the crime had occurred the most.
In 2021 the highest number of crime that occurred in a particular day are 330 crimes.
Bodily force such as Strong-Arms, hands, fist or feet are the weapons that are used in crimes.
Surprisingly Logistic Regression, Decision Tree and KNN Model has a same accuracy value. So all the three models are good for this data. 
New Year 2020 the highest number of crimes occurred which are around 500 crimes.
7th Street in Los-Angeles is where the highest number of crimes i.e 18k crimes.
There are lot of crimes where the weapons are unknow which means the one who is committing the crime has used the object which are convenient to them at the premises. We cannot guess or predict the weapons after my complete analysis on the data what ever we predict is just 50% of what we have just to get the idea. We cannot expect or guess 100% of the weapon to be cautions about.

### Future Work

This project can be further improved by taken time into consideration like at what tim ethe crimes are high. We can also combine different data set to get a in-depth knowledge about the weapons as many weapons are unknow. By considering the code of the area we can plot the most dangerous streets or areas on th emap by using new features which will be easy to reconize.

### References:

[1] https://monkeylearn.com/blog/data-preprocessing/

[2] https://www.techopedia.com/definition/32962/exploratory-data-analysis-eda

[3] https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

[4] https://medium.com/analytics-vidhya/los-angeles-crime-data-analysis-using-pandas-a68780d80a83 

[5] https://bja.ojp.gov/sites/g/files/xyckuh186/files/media/document/OverviewofCrimeAnalysis.pdf

[6] https://www.simplilearn.com/tutorials/machine-learning-tutorial/classification-in-machine-learning
