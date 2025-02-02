# NYPD-Arrests
New York Arrests

### Dataset Link: https://www.kaggle.com/datasets/justinpakzad/nypd-arrests-2023-dataset

## About Dataset
### Context
The NYPD Arrests Dataset (2023) consists of arrest records from the New York City Police Department for 2023. The data was sourced from NYC Public Data.

### Content
Each record in the dataset includes the following fields:

1. ARREST_KEY: Randomly generated persistent ID for each arrest.
2. ARREST_DATE: Exact date of arrest for the reported event.
3. PD_CD: Three-digit internal classification code (more granular than Key Code).
4. PD_DESC: Description of the internal classification corresponding with the PD code.
5. KY_CD: Three-digit internal classification code (more general category than PD code).
6. OFNS_DESC: Description of internal classification corresponding with KY code (more general category than PD description).
7. LAW_CODE: Law code charges corresponding to the NYS Penal Law, VTL, and other various local laws.
8. LAW_CAT_CD: Level of offense: felony, misdemeanor, violation.
9. ARREST_BORO: Borough of arrest. B(Bronx), S(Staten Island), K(Brooklyn), M(Manhattan), Q(Queens).
10. ARREST_PRECINCT: Precinct where the arrest occurred.
11. JURISDICTION_CODE: Jurisdiction responsible for arrest. Jurisdiction codes 0(Patrol), 1(Transit), and 2(Housing) represent NYPD, while codes 3 and above represent non-NYPD jurisdictions.
12. AGE_GROUP: Perpetrator’s age within a category.
13. PERP_SEX: Perpetrator’s sex description.
14. PERP_RACE: Perpetrator’s race description.
15. X_COORD_CD: Midblock X-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104).
16. Y_COORD_CD: Midblock Y-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104).
17. Latitude: Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326).
18. Longitude: Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326).

### Inspiration
The dataset can be used for a variety of research and analysis purposes, such as:

Crime Pattern Analysis: Investigate trends and patterns in criminal activity across different boroughs and precincts of New York City.
Law Enforcement Strategies: Examine the effectiveness of law enforcement strategies and policies based on arrest data.
Demographic Studies: Analyze the relationship between demographic factors (such as age, sex, and race of perpetrators) and arrest rates.
Geospatial Analysis: Utilize the geographic coordinates to map crime incidents and identify hotspots within the city.
Crime Hotspot Prediction: Develop a machine learning model to predict crime hotspots.


🔴 Dense red areas = Crime hotspots
🟡 Light red areas = Some crime but not extreme
⚫ No color = Low crime predictions
