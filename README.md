# MIST-4610-Project-2
 Team Name:
21479 Group 3

 Team Members:
Harrison Goldstein: https://github.com/harrisongold1210
Fiza Bhayani: https://github.com/fizab2329
Ethan Denbrok: https://github.com/EvanDebruyne
Luke Lambert: https://github.com/lhl88422
Raul Fernandez: https://github.com/rjf02

# Dataset Description
The dataset is sourced from incidents of crime in the City of Los Angeles dating back to 2020. The data is transcribed from original crime reports that are typed on paper.There are 847726 columns and 28 rows.

This dataset contains a range of information, each row represents a unique crime event. In this dataset, the 'DR_NO' column is of integer data type, representing the report number for each crime incident. The 'Date Rptd,' 'DATE OCC' columns are of date/time data types, capturing the reporting date, date of occurrence, and 'TIME OCC' in integer to represent the number of occurrences of the crime. Geographic details are captured through 'AREA' (integer) and 'AREA NAME (string) representing the numeric code and name of the geographic area. Other columns include 'Crm Cd' (integer) and 'Crm Cd Desc' (string) providing a numeric code and description for the type of crime, and 'Vict Age,' (string) 'Vict Sex,' and 'Vict Descent,' both in integer describing the victim's age, gender, and descent.

“Premis Cd” (integer) and “Premis Desc” (string) describe the numeric code and name of the crime location type (condo, police station, etc). Various codes and descriptions are provided for weapon use, and the status of the crime report, such as “Weapon Used Cd” (integer), “Status” (string), “Status Desc” (string); and “Crm Cd 1”, “Crm Cd 2”, “Crm Cd 3”, “Crm Cd 4” all in integers. Crime address is described specifically with “LOCATION” and “Cross Street” both in strings. Additionally, 'LAT' and 'LON' columns both in floats offer precise latitude and longitude coordinates for each crime incident.

# Data Dictionary 
![image](https://github.com/EvanDebruyne/MIST-4610-Project-2/assets/121137347/725cde03-1f4f-4f3b-9a01-072fa011d350)
![image](https://github.com/EvanDebruyne/MIST-4610-Project-2/assets/121137347/79e09852-eb34-42f8-bbb8-56e388605117)

# Question 1
How does data analysis, including demographics such as age and sex filtered by ethnicity, contribute to understanding the average profile of victims based on crime type descriptions?
![image](https://github.com/EvanDebruyne/MIST-4610-Project-2/assets/121137347/93da6fd1-5885-44a5-bae4-0371ad52ce65)

Analysis: This is useful information as there are many benefits to understanding the average age of victims of crimes in different areas. In addition, it is more beneficial to filter by crime type and can provide a lot of insight. For one this information can help targeted crime prevention strategies. Knowing the typical age of the affected victim groups helps law enforcement keep the targeted victims safe within each area. In addition, this data can be used for resource allocation and can be optimized based on knowing what demographic in this case age. Law enforcement can help allocate resources more effectively by prioritizing areas and age groups with higher cases of preventable crimes. In addition, public awareness and education will allow for individuals to be more aware of the common crimes in their area and the age groups they affect so that they themselves can be more proactive about their own safety. Furthermore, policymakers can use data to inform policy development aimed at improving public safety. In addition, a useful feature is evaluating the data over time by year which can help show the effectiveness of crime prevention measures. Lastly, this data visualization can help shed insight into the social and economic dynamics of communities. It is important how factors such as education levels and poverty rates influence crime patterns. Our data can be used to start to take a closer look at the socio-economic circumstances of each area within the data set.

The data for wanting to know the average age and the sex of the victims depending on the crimes committed is important information for the safety of citizens. Based on the situation, this graph shows which groups are more susceptible for a specific crime. For example, males at the average age of 32 are the most likely age for males to be victims of arson. This would make sense as most first-time male homeowners are in their 30s. Males are slightly less likely to fall victim to arson than females. While arson does not necessarily affect a specific sex, there are other crimes that females fall victim to and vice versa for males. For example, a bomb scare affects females more often than males. Knowing the age and sex of the victims affects by these crimes gives people a look into the crimes they are susceptible to and create prevention measures to keep them as safe as possible.

# Question 2
What insights can be gained from analyzing the distribution of weapon-related crimes, considering both the frequency of weapon usage per crime and the geographic areas where these crimes are most prevalent?
![image](https://github.com/EvanDebruyne/MIST-4610-Project-2/assets/121137347/732fd0eb-cead-4e5a-b635-ab68e4235209)
Analysis: This chart shows the patterns and trends in both the amount of weapon usage per crime and the areas where weapon-related crimes are most prevalent. Examining these data points, the person researching this topic can analyze all weapon-related offenses based on geographical content. Law enforcement strategies can be placed heavily in the areas that show a higher frequency of weapon related crimes. Public policy initiatives and community interventions can be created in the aim to reduce these crimes from happening as well. As a citizen, understanding this data is crucial in their safety as it can affect where they may travel and prepare for situations that may cause danger. Those who live in these areas may acknowledge this data and prepare measures to protect themselves. Over time, this data can be analyzed again after law enforcement strategies, public policy initiatives, and community interventions have been put into place to further see which precautions work best and other initiatives that may need to be worked on some more.

# Dataset Used
https://catalog.data.gov/dataset/crime-data-from-2020-to-present






