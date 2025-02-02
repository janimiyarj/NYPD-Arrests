# NYPD-Arrests
New York Arrests

## About Dataset
### Context
The NYPD Arrests Dataset (2023) consists of arrest records from the New York City Police Department for 2023. The data was sourced from NYC Public Data.

### Content
Each record in the dataset includes the following fields:

ARREST_KEY: Randomly generated persistent ID for each arrest.
ARREST_DATE: Exact date of arrest for the reported event.
PD_CD: Three-digit internal classification code (more granular than Key Code).
PD_DESC: Description of the internal classification corresponding with the PD code.
KY_CD: Three-digit internal classification code (more general category than PD code).
OFNS_DESC: Description of internal classification corresponding with KY code (more general category than PD description).
LAW_CODE: Law code charges corresponding to the NYS Penal Law, VTL, and other various local laws.
LAW_CAT_CD: Level of offense: felony, misdemeanor, violation.
ARREST_BORO: Borough of arrest. B(Bronx), S(Staten Island), K(Brooklyn), M(Manhattan), Q(Queens).
ARREST_PRECINCT: Precinct where the arrest occurred.
JURISDICTION_CODE: Jurisdiction responsible for arrest. Jurisdiction codes 0(Patrol), 1(Transit), and 2(Housing) represent NYPD, while codes 3 and above represent non-NYPD jurisdictions.
AGE_GROUP: Perpetrator’s age within a category.
PERP_SEX: Perpetrator’s sex description.
PERP_RACE: Perpetrator’s race description.
X_COORD_CD: Midblock X-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104).
Y_COORD_CD: Midblock Y-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104).
Latitude: Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326).
Longitude: Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326).

### Inspiration
The dataset can be used for a variety of research and analysis purposes, such as:

Crime Pattern Analysis: Investigate trends and patterns in criminal activity across different boroughs and precincts of New York City.
Law Enforcement Strategies: Examine the effectiveness of law enforcement strategies and policies based on arrest data.
Demographic Studies: Analyze the relationship between demographic factors (such as age, sex, and race of perpetrators) and arrest rates.
Geospatial Analysis: Utilize the geographic coordinates to map crime incidents and identify hotspots within the city.
Crime Hotspot Prediction: Develop a machine learning model to predict crime hotspots.
