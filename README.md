# Who Are We?  Exploring the Ethnic Evolution of Our Ancestors
## Identify and predict patterns in migration of ancestors by time period and country. 
project2-6 for Udacity Data Science course
See https://mtmssteffen.github.io/ for blog post 

https://github.com/user-attachments/assets/5b71cc86-e44f-4aea-ba98-d3b0d2bd081e


## Learning objective / Business Understanding
Our ethinic identity is normally defined by a specific country or region our ancestors came from.  However, for many people their ancestors came from multiple countries and regions as peoples migrated and intermarried.  This is reflected in DNA tests which list multiple countries of origin for specfic gene traits.  But what was the path that lead from these countries of origin to who I am today?  That path is recorded in our family history, the genealogy of the line of ancestors going from us to these countries of origin.  Unlike DNA tests, our genealogy doesn't come with a one-page summary of all the steps from the past to the present.   

While most ancestors lived in the same location all their lives, at certain periods in history in certain countries family groups or individuals would move to a new country.  Visualizing the times and places of these major changes in ancestors lives can give insight into the life experiences that shaped their lives and lead to the places and times we now live in.  Genealogy records of life events such as birth and death dates and locations give the raw data for identifying these inflection points in our family's path.  However, this genealogy data is not in a consistent standard format, locations have changed names over the years and boundaries of countries have shifted, and many records give only dates but lack location.  

This project makes a first step in filling out the gaps in ancestor records by modeling the patterns of which time periods and which locations were more likely to have movement from ancestral homelands.  Specific business questions addressed include:
- Which countries were the home location ancestors originated from?
- Which countries had the highest numbers of ancestors who migrated to other countries?
- Which time periods had the highest numbers of ancestors who migrated to other countries?


## Data Sources / Data Understanding / Files in the Repository
Family history compiled, cleaned, labeled, merged, and analyzed from multiple sources from 2009 - 2024, and summarized in:  

 - `Ancestor_data.csv`:  Genealogy of ancestors, uniquely ID each individual, giving family surname, gender, birth & death year & location, IDs of parents, and an intepretation of the country of origin.
 - `FamilyAtlasPlacesGeocode.csv`:  List of raw locations from Ancestor_data run through the Family Atlas geocoding tool to generate standard location names and latitute-longitude.  About half of the raw locations had automated matches, and close matches required manual review and updating.
- `DSN-Project-2-6.ipynb`: Jupyter notebook with the complete CRISP-DM process including Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, Deployment
- `amap.mp4`:  Animation of Estimated Country data from the Ancestor_data.csv file for comparison with the analysis and models created by this project.
- `README.md`: This file containing the overview of this project   


## Libraries Used
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.8+.
- pandas - For data manipulation and analysis
- numpy - For numerical operations
- matplotlib - For creating visualizations
- seaborn - For enhanced visualizations
- scikit-learn - For machine learning algorithms
      
## Libraries would use if more time and in follow on projects
- statsmodels - For statistical modeling
- scipy - For statistical modeling
- networkx - For direct graph representation of genealogy relationships, cluster analysis, and graph metrics
  

## Summary of Results
The analysis of ancestral migration patterns revealed several interesting insights:
- Migration patterns
- 
## Acknowledgements
- FamilySearch.com is the original source for the majority of the genealogy complied in the ancestor_data.csv file
- Other sources for genealogy records include BillionGraves.com, Ancestry.com, MyHeritage.com
- RootsMagic.com provided tools for extracting genealogy data and compiling in text csv files for analysis
- RootsMagic.com provided the Family Atlas tool for geocoding locations in genealogy records used in this analysis
- 


