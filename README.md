# Prime Video Dashboard

### Dashboard Link : https://github.com/AhsanIqbal-web/Prime-Video-Dashboard

## Problem Statement

Despite hosting discussions on Prime Video encompassing a variety of topics, there is a lack of cohesive insight into audience preferences, viewing trends, and content attributes such as ratings, total shows, and directors. The absence of a structured analytical framework impedes the ability to discern audience sentiments, identify popular content, and make informed decisions regarding content curation and platform optimization. Consequently, there is a pressing need to develop a Power BI dashboard that consolidates, analyzes, and visualizes Prime Video data, including audience demographics, show ratings, total shows, and directors. This dashboard aims to address the following key challenges:

Incomplete Audience Understanding: The current lack of visibility into audience demographics and preferences hinders the ability to tailor content to viewers' interests effectively.

Limited Insight into Content Performance: Without a centralized analytics platform, it is difficult to assess the popularity and success of individual shows, directors, or ratings categories, impeding data-driven content decision-making.

Suboptimal Resource Allocation: Absent actionable insights, resources may be allocated inefficiently across content creation, promotion, and audience engagement initiatives, leading to missed opportunities for growth and optimization.

Untapped Potential: Prime Video discussions represent a valuable source of feedback and engagement opportunities that remain underutilized due to the absence of a robust analytics framework.

Addressing these challenges through the development of a Power BI dashboard will empower content creators, moderators, and stakeholders with actionable insights derived from data analysis. By gaining a deeper understanding of audience preferences, content performance, and platform dynamics, Prime Video can enhance user engagement, optimize content strategies, and drive platform growth effectively.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           
