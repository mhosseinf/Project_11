PROJECT 1: GLOBAL NATURAL DISASTERS 

GLOBAL NATURAL DISASTERS VS. TEMPERATURE

44 YEAR ANALYSIS

1979-2023

Data Visualisation Project

#Dominique Spencer, Hieu Lam, Hossein Falsafi, & Ryan James

#University of Western Australia

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/mhosseinf/Project_11/assets/141802851/201632ed-613c-4a8b-b1a1-037ca072d33f)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Abstract

With economic demands soaring, population growth rising, and urban sprawl expanding, humans are becoming more exposed and aware to environmental disasters (natural and non-natural). The purpose of this research project is to analyse the correlation between the number of environmental disasters and the impact this is having on global temperatures over the last 44 years (1979-2023). Furthermore, these variables will be intentionally scrutinized to identify any significant trends and/or correlations to see if they are statistically significant or not. 

Introduction

With the Earth spinning on its axis, rotating and in constant orbit, environmental disasters are largely uncontrollable. The Earth’s landmass constitutes 29% of the total surface area and the remaining 71% is consumed by large bodies of ocean water. Over the last 44 years (1979-2023), the needs of human society are exponentially growing and changing, which is causing urban sprawl to expand in geographical parts of the world. This in essence is increasing the likelihood of humans experiencing environmental phenomena (natural and non-natural). 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Sources

- EM-DAT: THE INTERNATIONAL DISASTER DATABASE
    - A global database which contains data on the occurrance and impacts of natural disasters since 1900.
    - Collects data from an array of international agenices (United Nations, Research Institutions etc.)

 - OPEN WEATHER MAPS API
    - Provides historical, current and forecasted weather data via lightspeed APIs.
    - Histroical timestamp of temperature data was used from 1979-2023.
  
- GISS
    - NASA's Goddard Institute for Space Studies.
    - Predicts atmospheric and climate changes.
 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Scope

This project will remain within the bounds of 'global natural disaster data' and the 'local & global temperature data' variables spanning over the last 44 years (1979-2023) with the strong intentions of identifying and scrutinising any significant trends and/ or correlations between them.

Furthermore, the following questions will be dissected with a Jupyter Notebook:

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(1)	What is the influence of geographic coordinates on the frequency of natural disasters? Compare the Northern Hemisphere Vs. Southern Hemisphere.



![image](https://github.com/mhosseinf/Project_11/assets/141802851/ff6a1ac0-d67e-4a0e-9a82-35462001c816)


- The highest number of disasters per region: 'South-Eastern Asia', 'Southern Asia', and 'Eastern Asia'.
    - Primary Tectonic plate locations: 'Eurasian' and 'Indian' plates.
    - Reasoning: Significantly dense landmass region comrpising of complex mountain system and plateaus.
 
- The lowest number of disasters per region: 'Australia & New Zealand', 'Northern Europe', and 'Caribbean'.
    - Prinmary tectonic plate locations: 'Indo-Australia', part of the 'Eurasian', and 'Caribbean' plates.
    - Reasoning: Regions of less landmass per tectonic plate and surrounded by large volumes of oceanic water (experience less frequent disasters)

- Limitation:
    - CSV.FILE data had empty Longitude and Latitude values for large portions of the data.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(2)	What is the correlation between natural disaster frequency and average temperatures over time?



![image](https://github.com/mhosseinf/Project_11/assets/141802851/75e2ab3d-e65d-48e3-abb3-876d080c9f80)



![image](https://github.com/mhosseinf/Project_11/assets/141802851/5b1eda61-2488-48ec-9bae-75047a5d88bb)



![image](https://github.com/mhosseinf/Project_11/assets/141802851/f911c3bf-792e-4f98-85ea-2f161dd094cc)




--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(3)	What category of natural disaster is more likely to occur during specific seasons?


Dataframe for Disaster and Temperature

![image](https://github.com/mhosseinf/Project_11/assets/141802851/0636802c-1ea7-4e68-869e-c26028a00649)

- Number of original rows count: 23,252
- Number of rows after applying API query temperature data, 2,277

Local Data - Open Weather API

![image](https://github.com/mhosseinf/Project_11/assets/141802851/d679b1b0-5443-4b84-b371-d70ae6bede7d)

Correlation between Natural Disaster Frequency Vs. Average Local Temperature

![image](https://github.com/mhosseinf/Project_11/assets/141802851/d5957d87-c070-42a3-8e98-5734755f9c81)

- Correlation Summary for Natural Disaster Frequency Vs. Average Local Temperature:
    - The calculated r-value coefficient of -o.o yields a very weak, negative linear relationship.
 
Natural Disaster Frequency Vs. Global Average Temperatures

![image](https://github.com/mhosseinf/Project_11/assets/141802851/fae54bde-5373-49ac-9fa5-4e1d23a3a51d)

Correlation between Natural Disaster Frequency Vs. Average Global Temperature

![image](https://github.com/mhosseinf/Project_11/assets/141802851/181f993d-adc4-4a7b-80b3-1eaaeff164c8)

- Correlation Summary for Natural Disaster Frequency Vs. Average Local Temperature:
    - The calculated r-value coefficient of 0.73 yields a moderate to strong linear realtionship.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(4)	Are there global hotspots for specific disaster categories?


Floods (Natural): #1

![image](https://github.com/mhosseinf/Project_11/assets/141802851/ee870913-104d-4132-b93a-63d678002c8e)

Storms (Natural): #2

![image](https://github.com/mhosseinf/Project_11/assets/141802851/4c44f9e5-4db8-4d94-94d5-aff69e496387)

Earthquakes (Natural): #3

![image](https://github.com/mhosseinf/Project_11/assets/141802851/256a3537-46c9-4034-8c61-5ed07b347324)

Epidemic (Human): #4

![image](https://github.com/mhosseinf/Project_11/assets/141802851/c374de04-b79a-4291-a256-13469723e654)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(5)	Are there any noticeable trends in different types of natural disasters over time?


![image](https://github.com/mhosseinf/Project_11/assets/141802851/01a42572-6fc3-4426-a3e9-84f7c271e0b3)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

(6)	Which countries might be the ‘safest’ from, or most ‘at risk’ of natural disasters? (BONUS)


Visual represent the top 10 countries with the ‘most disasters’:

![image](https://github.com/mhosseinf/Project_11/assets/141802851/9d8bcbec-115f-4428-a74f-372c9e8bc3b1)


Visual represent the top 10 countries with the ‘fewest disasters’:

![image](https://github.com/mhosseinf/Project_11/assets/141802851/b105ed98-2240-4890-bac3-36e46252dec9)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
