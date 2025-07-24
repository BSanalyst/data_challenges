# Problem Statement
Your task is to transform and analyze the Global Terrorism Database (GTD) Sample dataset using Databricks to uncover insights into terrorist activities worldwide from 1970 to 2017. You will clean the dataset to handle missing or inconsistent data, aggregate statistics to identify patterns in attack frequency and casualties, and join with a derived region summary table to enrich your analysis. The goal is to answer key questions about regional terrorism trends, providing a foundation for understanding global security dynamics through data wrangling techniques.

# Questions
## Data Cleaning: 
How can you handle missing values in the latitude, longitude, and city columns, and what impact does this have on the dataset's usability for geographic analysis?
## Aggregation: 
Which regions have experienced the highest number of terrorist attacks per year, and what are the total casualties (fatalities plus wounded) associated with these attacks?
## Derived Table and Joining: 
How can you create a derived table summarizing average annual attacks and total casualties by region, and what new insights emerge when you join this table with the main dataset?
## Pivoting and Analysis: 
How do the frequencies of different attack types (e.g., Bombing, Armed Assault) vary across regions, and which attack type is most common in the region with the highest attack count?
## Unpivoting and Flexibility: 
After pivoting attack counts by region and attack type, how can unpivoting the data help you compare trends across all regions and attack types in a single analysis?
## Trend Identification: 
Which regions show the most significant increase in attack frequency or casualties over the decades (e.g., 1970s vs. 2010s), and what might this suggest about changing terrorism patterns?

# Guidance for Users
Dataset Source: Download the dataset from https://www.kaggle.com/datasets/START-UMD/gtd and upload it to your Databricks file system as globalterrorismdb_0718dist.csv.
Tools: Use the provided PySpark code as a starting point, modifying it to address the questions above.
Output: Save your transformed tables (e.g., terrorism_pivot, terrorism_unpivot, terrorism_region_trends) and use Databricks’ display() function to visualize results, such as bar charts or line plots.
Extension: Explore additional questions, like analyzing trends by country_txt or success of attacks, to deepen your analysis.
