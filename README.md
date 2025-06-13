# Pittsburgh: Condemned-DeadEnd-Properties
Exploring Datasets + Collecting Data-Driven Insights + Proposing a Solution

## Files Included & Use:
1. **deadend.csv** --> original dataset obtained from [Condemned Properties](https://data.wprdc.org/dataset/condemned-properties/resource/0a963f26-eb4b-4325-bbbc-3ddf6a871410)
2. **no_dupe_df.csv** --> cleaned dataset with parcel_id duplicates removed + score range being fixed
3. **property assessment parcel data.csv** --> from [Allegheny County Property Assessments Table](https://data.wprdc.org/dataset/property-assessments) to fill in missing address columns (not in data files folder -- too big of a file.)
4. **city_owned_property.csv** --> from [City Owned Properties Dataset](https://data.wprdc.org/dataset/city-owned-properties/resource/e1dcee82-9179-4306-8167-5891915b62a7) to fill in missing address columns for properties owned by City of Pittsburgh
5. **alleghney_2802.csv** --> saved for data related to our parcel_id in condemned/dead-end properties dataset for reference. 
6. **city_df_470.csv** --> saved for only working with data related to our parcel_id in condemned/dead-end properties dataset for reference.
7. **final_draft_df** --> dataset with most addresses filled out (from Allegheny + City Property dataset combined)


## EDA + Data Cleaning File
### What was done:
- Exploring the dataset, finding patterns, and any insights
- Cleaning data
- Creating visualizations (whole, condemned properties, dead-end properties)
- Marking down insights

### Detailed Insights Summarized:
**Condemned or Dead-End**
- Approximately 79.2% of Properties are Condemned
- Approximately 20.8% of Properties are Dead-End

**Fail Inspection**
- Approximately 79.3% of Condemned Properties Fail Inspection.
- Approximately 10.6% of Dead-End Properties Fail Inspection.

**Scores Evaluation**
*   All Dead-End Properties having a score of 1 show that they are structurally intact with no immediate observable danger. **[Source](https://engage.pittsburghpa.gov/pli-demolition-engagement)**
*   Condemned Properties scores range from 1-4, with 4 being imminently dangerous, these can be the properties/areas the city prioritizes.


**Score 4 Properties**
*   The 3 owners of the 3 Score 4 Properties are: City of Pittsburgh, Gill John, and Gardner Luella B.
*   By Identifying their Addresses with the cleaned dataset, we could prioritize these high-risk properties to obtain private demolition permit or a building permit to repair.

**Addresses**
*   Most addresses in the dataset is listed as "No primary address specified". 
*   This will have to be filled in to figure out which areas should be prioritized first.


## Combining Datasets
### **Dataset 1: [Allegheny County Property Assessments - Property Assessments Parcel Data](https://data.wprdc.org/dataset/property-assessments/resource/9a1c60bd-f9f7-4aba-aeb7-af8c3aaa44e5)**
### What was done:
- 

### Detailed Insights Summarized:
- 


### **Dataset 2: [City-Owned Properties Dataset](https://data.wprdc.org/dataset/city-owned-properties/resource/e1dcee82-9179-4306-8167-5891915b62a7)**
### What was done:
- 

### Detailed Insights Summarized:
- 


