# CRIME HOTSPOT DETECTION 

## Overview
The objective of this project is to develop a machine learning model that accurately identifies crime hotspots in Los Angeles. Using LAPD crime data, the model will deliver actionable insights to enable targeted security recommendations for clients in high-risk areas.
The dataset includes various features , and these features are described below :
|Sr.no|Features name|Description |
 |-|-|-|
|1)|DR_NO|Division of Records Number: Official file number made up of a 2 digit year, area ID, and 5 digits |             
|2)| Date_Rptd|MM/DD/YYYY |             
|3)|DATE_OCC|MM/DD/YYYY |             
|4)|TIME_OCC|In 24 hour military time |         
|5)|AREA|The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department|              
|6)|AREA_NAME|Name designation that references a landmark or the surrounding community    |              
|7)|Rpt_Dist_No|A four-digit code that represents a sub-area |          
|8)|Part 1-2|"No description"  |             
|9)|Crm Cd|Indicates the crime committed   |                
|10)|Crm_Cd_Desc |Defines the Crime Code provided   |          
|11)|Mocodes|Modus Operandi: Activities associated with the suspect in commission of the crime|           
|12)|Vict_Age|Two character numeric |               
|13)|Vict_Sex| F - Female M - Male X - Unknown  |        
|14)|Vict_Descent|Descent Code: A - Other Asian B - Black C - Chinese D - Cambodian F - Filipino G - Guamanian H - Hispanic/Latin/Mexican I - American Indian/Alaskan Native J - Japanese K - Korean L - Laotian O - Other P - Pacific Islander S - Samoan U - Hawaiian V - Vietnamese W - White X - Unknown Z - Asian Indian |      
|15)|Premis_Cd|Type of structure, vehicle, or location where the crime took place |     |16)|Premis_Desc|Defines the Premise Code provided  |        
|17)|Weapon_Used_Cd|The type of weapon used in the crime |    
|18)|Weapon_Desc|Defines the Weapon Used Code provided |       
|19)|Status|Status of the case. (IC is the default) |                 
|20)|Status_Desc|Defines the Status Code provided  |           
|21)|Crm_Cd_1|Indicates the crime committed. Crime Code 1 is the primary and most serious one. Crime Code 2, 3, and 4 are respectively less serious offenses. Lower crime class numbers are more serious |              
|22)|Crm_Cd_2| May contain a code for an additional crime, less serious than Crime Code 1 |          
|23)|Crm_Cd_3|May contain a code for an additional crime, less serious than Crime Code 1   |       
|24)|Crm_Cd_4|May contain a code for an additional crime, less serious than Crime Code 1   |        
|25)|LOCATION |Street address of crime incident rounded to the nearest hundred block to maintain anonymity  |              
|26)|Cross_Street|Cross Street of rounded Address|      
|27)|LAT| Latitude|                    
|28)|LON|Longitude |

 ## Steps performed
 1. Import Libraries : 
    Load the necessary Python libraries for data analysis
 2. Import Data :
    Import the dataset containing the features  
 3. Data Clean :
    Check Null values, Drop unwanted features   
 4. Data Visualizations :
    Visualize the data to gain insights and detect trends
 5. Feature Engineering :
    From existing columns Created new features like, Hour, Year, Month etc.
 7. Machine Learning :
    Develop and evaluate machine learning models
    i. K- means
    Check the Silhouette Score for AcAccuracy 
9. Cluster Analysis
    Visualize the data on the basis of clusters
   
