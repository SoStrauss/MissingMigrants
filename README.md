# MissingMigrants
## Python-coded analyses of the Missing Migrants dataset (IOM), including Tableau visualization

## Project: Missing Migrants

### 1. Summary of the data
**Data source:**

-	Collected by the Missing Migrants Project, an initiative implemented by the International Organization for Migration (IOM) since 2014. Missing Migrants Project is a joint initiative of IOM's Global Migration Data Analysis Centre (GMDAC) and Media and Communications Division (MCD).
-	"IOM's Missing Migrants Project" https://missingmigrants.iom.int/ 
-	Research behind this project began with the October 2013 tragedies, when at least 368 individuals died in two shipwrecks near the Italian island of Lampedusa.
-	GeoJSON file provided by CareerFoundry for educational purpose.

**Data collection method:**

-	Missing Migrants Project gathers information from diverse sources: official records (including from coast guards and medical examiners), media reports, NGOs, surveys and interviews of migrants. 	
-	Mediterranean region: relevant national authorities to IOM field missions. Data are also obtained by IOM and other organizations that receive survivors at landing points in Italy and Greece. IOM and UNHCR also regularly coordinate to validate data on missing migrants in the Mediterranean.
-	US/Mexico border: U.S. county medical examiners, coroners, sheriff’s offices, media reports for deaths occurring on the Mexican side of the border.
-	Africa: media and NGOs, including the Regional Mixed Migration Secretariat and the International Red Cross/Red Crescent.
-	Missing Migrants Project uses social and traditional media reports to find data, which are then verified by local IOM staff whenever possible. New entries are checked against existing records to ensure that no deaths are double-counted. In all regions, Missing Migrants Project data represent a minimum estimate of the number of migrant deaths.

**Data content:**

-	Missing Migrants Project tracks the deaths and disappearances of migrants, including refugees and asylum-seekers, who have died or gone missing in the process of migration towards an international destination.
-	Missing Migrants Project counts migrants who have died at the external borders of states, or in the process of migration towards an international destination, regardless of their legal status. The Project records only those migrants who die during their journey to a country different from their country of residence.
-	Data include the deaths of migrants who die in transportation accidents, shipwrecks, violent attacks, or due to medical complications during their journeys
-	Includes the number of corpses found at border crossings that are categorized as the bodies of migrants, on the basis of belongings and/or the characteristics of the death (i.e., decedent is found without any identifying documentation in an area known to be on a migration route).
What is excluded:
-	Deaths that occur in immigration detention facilities or after deportation to a migrant’s homeland, as well as deaths more loosely connected with migrants´ irregular status, such as those resulting from labour exploitation. 
-	Migrants who die or go missing after they are established in a new home are also not included in the data, so deaths in refugee camps or housing are excluded. 
-	The deaths of internally displaced persons who die within their country of origin are also excluded.

### 2. Potential Limitations/Biases:

-	Due to the complexities of data collection, the figures presented are likely an undercount.
-	Majority of deaths are of migrants travelling by irregular means, they often occur in remote areas chosen because of a lack of legal routes. As a result, bodies are not always found quickly, if it all, and deaths may not be systematically reported to authorities.
-	When deaths occur at sea or in other bodies of water, many of the deceased may not be recovered, and without passenger lists, the precise number of missing is unknown.
-	Involvement of criminal actors, border guards, and others in the process of irregular migration might make survivors fearful of reporting deaths, and some deaths may even be actively covered up.
-	Data on migrant deaths and disappearances are also challenging to collect as consistent reporting by states on the deaths of non-nationals in transit, or nationals who have died while in transit abroad is very scarce. Few official sources collect and publish data on migrant deaths.  Often incidents come to light through media sources, which may have incomplete and infrequent coverage.
-	Data on missing migrants tend to over-represent parts of the world where there is better media coverage and official reporting of deaths, such as Europe and the Mediterranean. Comparatively few data on migrant deaths are recorded in areas of the world with large volumes of irregular migration, despite the many dangers migrants face in these regions. For example, some experts believe that more migrants die while crossing the Sahara Desert than in the Mediterranean Sea.
-	Locations in most cases are approximates.
-	While the location and cause of death can provide strong evidence that an unidentified decedent should be included in Missing Migrants Project data, this should always be evaluated in conjunction with migration history and trends.
-	While ideally, all incidents recorded would include entries for each of the variables, the challenges described above mean that this is not always possible. The minimum information necessary to register an incident is the date of the incident, the number of dead and/or the number of missing, and the location of death.


### 3. Data Relevance

-	Migration Patterns Analysis: Explore trends and patterns in migration incidents to understand the most affected regions and routes.
-	Gender and Age Analysis: Investigate the demographics of migrants to identify gender and age-related vulnerabilities.
-	Survival and Mortality Analysis: Analyze survival rates and causes of death to highlight risks and challenges migrants face.
-	Temporal Analysis: Examine incidents over time to identify any temporal patterns or changes.
-	Geospatial Analysis: Utilize geographical coordinates to map migration routes and incident locations.   


**NOTE:**

The Missing Migrants Project is an “incident-based” dataset, meaning that each entry in the database represents a single occurrence in which an individual or group of individuals die during migration or at international borders in one particular place and time. In some cases, official statistics are not disaggregated by the incident, in which case the entry will be marked as a “cumulative total.”

## Content of folders:

**1. Project Management**
- Project Information_updated
- Project Brief
  
**2. Data**
- Original data
- Prepared data
  
**3. Scripts**
  1. Check and compare datasets
  2. Update_2. Data Preparation_Quality and consistency checks
  3. Update_3. Exploratory Analysis Exploring Relationships in Visualizations
  4. Update_4. Geospatial Analysis
  5. Supervised Machine Learning_Regression
  6. Unsupervised Machine Learning_Clustering
  7. Update_7. Analyzing & Forecasting Time Series Data_year_month
  8. Preparing Tableau Storyboard
     
**4. Analysis**
- Reports

## Project deliverable: Tableau Visualization

[Missing Migrants (IOM)](https://public.tableau.com/views/MissingMigrantsIOM/Story1?:language=de-DE&:display_count=n&:origin=viz_share_link)
