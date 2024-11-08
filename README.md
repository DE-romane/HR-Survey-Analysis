**HR Survey Analysis**

**The Situation**  
You’ve recently joined the Seattle Department of Public Works as an HR Associate.

**The Assignment**  
The city conducted a survey of approximately 1,500 public works employees to assess job satisfaction and pinpoint ways to enhance motivation and engagement. Your task is to analyze this survey data and prepare a visual summary for the HR leadership team.

**Objectives**  

1. **Data Profiling & Quality Assurance**: Review and clean the data to address any quality issues.
2. **Data Preparation**: Reformat the data for effective visualization.
3. **Data Visualization & Insights**: Create visualizations to highlight key findings and provide actionable recommendations.
--------
**Objective 1: Data Profiling & Quality Assurance**

1. Calculate key metrics (minimum, maximum, count, and number of blanks) for each numerical field.
2. Remove records with any blank responses.
3. Remove records with duplicate values across all fields.
4. For the *Department* and *Question* fields:
   - Calculate the count or frequency of each unique value.
   - Standardize any inconsistencies in these fields.
---
**Objective 2: Data Preparation for Visualization**

1. Create a new tab labelled **Chart Source** and compile a unique list of all survey questions.
2. For each question:
   - Calculate the count of records associated with each response type (1 through 4).
   - Compute the average response, excluding any zero values.
3. Add new columns to convert these counts into percentages based on the total responses for each response type (1, 2, 3, or 4).
4. Copy and paste the data as values, then sort the questions in descending order by the average response.
---
**Objective 3: Visualize the Data**

1. Create a 100% stacked bar chart, sorting questions by highest average response at the top.
2. Use shades of orange/red for negative responses (1,2) and shades of blue for positive responses (3,4).
3. Add data labels; remove the x-axis, title, and vertical gridlines; format chart elements for readability.
4. Generate insights and recommendations for HR leadership based on the visualization.
5. *Bonus:* Adjust the chart to align positive responses to the right and negative to the left using calculated columns.
---

