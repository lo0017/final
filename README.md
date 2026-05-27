# Food Access in the United States

## Table of Contents
- [Motivation](#motivation)
- [Research Questions](#research-questions)
- [Data Sources](#data-sources)
- [Acquiring and Normalizing the Data](#acquiring-and-normalizing-the-data)
- [Analysis Process](#analysis-process)
- [Problems and Challenges](#problems-and-challenges)
- [Technologies Used](#technologies-used)
- [Key Findings](#key-findings)
- [Future Improvements](#future-improvements)
- [Sources](#sources)

---

# Motivation

Food access is an important public health and geographic issue that affects communities across the United States. Limited access to grocery stores can influence nutrition, transportation costs, and long-term health outcomes.

I chose this project because I wanted to better understand how geographic location influences food accessibility, especially within rural communities and Appalachia. Living in West Virginia made this topic personally meaningful because many Appalachian communities experience transportation barriers and long travel distances to reach grocery stores.

Through this project, I hoped to identify national food access patterns while also examining how those patterns appear at the local county level in West Virginia and Kentucky.

---

# Research Questions

This project focused on the following questions:

1. What geographic patterns of low food access appear across the United States?

2. How do food access rates differ across demographic groups?

3. How do food access patterns differ between rural and urban communities?

4. How does food access vary across counties in West Virginia and Kentucky?

---

# Data Sources

The primary dataset used in this project was:

- USDA Food Access Research Atlas

The dataset contains demographic, geographic, and food accessibility variables across the United States at the census tract and county levels.

---

# Acquiring and Normalizing the Data

The data was downloaded from the USDA Food Access Research Atlas and imported into Python for analysis. Initial exploration and validation were also completed in Excel.

Steps taken during data preparation included:

- Cleaning missing and inconsistent values
- Filtering relevant variables
- Creating county-level summaries
- Comparing rural and urban classifications
- Merging demographic and geographic information
- Creating geographic visualizations and maps

The data required extensive organization because the dataset included a large number of demographic and geographic variables.

---

# Analysis Process

The project began with national-level analysis to identify overall food access patterns across the United States. After identifying broader trends, the analysis narrowed to:

- Demographic comparisons
- Rural versus urban analysis
- West Virginia county analysis
- Kentucky versus West Virginia county comparisons
- Interactive geographic visualizations

Python was used heavily throughout the project for data cleaning, aggregation, analysis, and visualization creation.

---

# Problems and Challenges

Several challenges occurred throughout the project:

- Managing a very large dataset with many variables
- Tracking changes across multiple notebooks
- Accidentally deleting columns needed later in the analysis
- Organizing visualizations and maintaining consistent outputs
- Merging geographic and demographic data correctly
- Interpreting rural versus urban food access differences without oversimplifying the results

One major challenge was keeping track of transformed datasets while continuing to create new visualizations and analyses.

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data cleaning, analysis, and visualization |
| Excel | Initial data exploration and validation |
| Pandas | Data manipulation and aggregation |
| Plotly | Interactive visualizations and mapping |
| GeoPandas | Geographic analysis |
| Git | Version control |
| Jupyter Notebook | Analysis workflow and coding environment |

---

# Key Findings

Some of the major findings from this project included:

- Food access challenges are not distributed evenly across the United States.
- Low-income populations experienced the highest levels of limited food access overall.
- Rural communities often face greater transportation and distance barriers.
- Food access disparities can vary significantly between neighboring counties.
- West Virginia and Kentucky both showed localized food access disparities, although their geographic patterns differed.

---

# Future Improvements

Future improvements for this project could include:

- Expanding analysis to additional Appalachian states
- Incorporating transportation availability data
- Comparing food access changes over time
- Including healthcare outcome correlations
- Building a fully interactive dashboard for county-level exploration

---

# Sources

- USDA Food Access Research Atlas
- U.S. Census demographic data
- Python documentation
- Plotly documentation
- Pandas documentation