### How has the frequency of terrorist attacks changed over time globally, and which year recorded the highest number of incidents?

**Process:**  
- Load the dataset  
- Clean missing or invalid `iyear` values by filtering out nulls and ensuring valid years (e.g., 1970–2017)  
- Aggregate the total number of attacks per year  
- Identify the year with the peak attack count

---

### Which region has been the most affected by terrorist attacks in terms of total incidents, and how does this compare to the region with the highest casualty count (fatalities plus wounded)?

**Process:**  
- Clean missing values in `nkill` and `nwound` by imputing with 0 where necessary  
- Aggregate the total number of attacks and total casualties (`nkill` + `nwound`) by `region_txt`  
- Compare the rankings of regions by these metrics

---

### What are the most common target types for terrorist attacks worldwide, and how can you determine which target type has caused the greatest number of casualties?

**Process:**  
- Address inconsistencies in `target1` (e.g., handle missing or malformed entries by imputing with "Unknown")  
- Aggregate the count of attacks by `target1`  
- Calculate total casualties by `target1` to identify the most impacted target type

---

### Which attack type has been the most prevalent globally, and how does its distribution vary across the top three regions by attack frequency?

**Process:**  
- Clean potential inconsistencies in `attacktype1_txt` (e.g., standardize case or handle missing values with "Unknown")  
- Aggregate the count of attacks by `attacktype1_txt`  
- Derive a table of top three regions by total attacks  
- Join this with the main dataset to analyze the distribution of attack types

---

### How can you identify the cities with the highest number of attacks, and what additional insights can you gain by linking this data with regional casualty trends?

**Process:**  
- Clean missing city values by imputing with "Unknown"  
- Aggregate the total number of attacks by city  
- Create a derived table summarizing total casualties by `region_txt`  
- Join this with the city-level data to explore correlations between attack frequency and regional casualty rates