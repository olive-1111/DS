# Python for Data Science: COVID-19 Trend Analysis

A data-driven investigation into global pandemic trends, built using a custom-sourced dataset from Kaggle and refactored from a legacy Python course.


## ANALYSIS OVERVIEW
* **Data Sourcing:** Unlike a standard tutorial, I independently sourced and integrated a multi-file dataset from Kaggle, requiring custom preprocessing and merging logic.
* **Trend Identification:** Analyzing confirmed cases, recovery rates, and mortality trends across global regions.
* **Time-Series Aggregation:** Grouping complex date-based data to visualize the progression of the virus over time.

## CHALLENGES & SOLUTIONS

### **1. Independent Data Integration**
The tutorial did not provide raw data, which forced a "real-world" workflow:
* **The Unicode Hurdle:** Solved `UnicodeDecodeError` issues by identifying the correct encoding (e.g., `unicode_escape`) for regional CSV files.
* **Label Mapping:** Because my Kaggle data differed from the tutorial, I meticulously mapped labels (e.g., `Region`, `Confirmed`, `MedHouseVal`) to ensure the logic remained sound despite variable name changes.

### **2. Aggregation Logic**
* **The GroupBy Struggle:** Overcame `TypeError` roadblocks in Pandas by ensuring mathematical operations (like `.sum()`) were only applied to numerical columns, while maintaining categorical "Date" and "Region" labels for the final plot.

### **3. Meticulous Debugging**
* Spent significant time aligning the "basic" lessons from the course with "advanced" implementation needs, effectively skipping redundant theory to focus on high-impact data extraction.
