# Netflix Dataset Analysis

I transitioned from a career in the creative industry to pursuing my passion for data engineering. My love for film drives my current project, where I analyze a dataset from Netflix. This dataset encompasses information about the TV shows and movies available on the platform from 2018 to 2021\.

## Overview

As someone with a strong foundation in data analytics and a passion for creative business applications, I designed this notebook to transform a raw Netflix dataset into a refined, analysis-ready format. The notebook focuses on:

- Downloading and reading the dataset  
- Cleaning and preprocessing data  
- Handling missing values intelligently  
- Identifying and correcting data inconsistencies  
- Preparing date formats and basic deduplication

## Key Steps

1. **Data Ingestion**: Import `netflix_titles.csv` or download directly via `gdown`.  
2. **Missing Value Treatment**:  
   - Filled `director`, `cast`, and `country` with `"Unknown"`  
   - Addressed misplacements between `duration` and `rating` columns  
3. **Date Conversion**: Parsed `date_added` as datetime for further time-based insights.  
4. **Data Deduplication**: Checked for and addressed duplicate records.  
5. **Initial Exploration**: Previewed distributions and missing data summaries.  
- 

## Potential Next Steps

- Visualize content trends over time  
- Build a recommendation engine  
- Cluster shows by attributes (e.g., genre, duration)  
- Analyze regional content availability

---

