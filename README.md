# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis was to determine parameters of successful Kickstarter campaigns with the theatre category and play subcategory. 

## Analysis and Challenges

### An analysis of Outcomes Based on Launch Date was performed by translating the date campaigns were launched into a year format. This information was placed in a pivot table to visualize months by outcomes (successful, failed, live and canceled) for all theatre Kickstarter campaigns. A pivot chart was created in the form of a line graph with markers ![Outcomes_vs_Goals] (https://github.com/AaraniSivasekaram/Kickstarter-Analysis/commit/d4240ec0ff2e60b0e303e8ac5c592de1fe7c8123).

### An analysis of Outcomes Based on Goals was performed by creating 12 different goal ranges and using the COUNTIFS function. Data from all Kickstarter campaigns was filtered using the COUNTIFS function to include only data from plays, then data was separated by the different goal ranges, then separated by successful, failed and live campaign outcomes. This data was then translated into percentages of successful, failed and live plays, within the different goal ranges. A pivot chart was created in the form of a line graph with markers ![Theatre_Outcomes_vs_Goals] (https://github.com/AaraniSivasekaram/Kickstarter-Analysis/commit/d4240ec0ff2e60b0e303e8ac5c592de1fe7c8123). 

### Challenges and difficulties encountered during this analysis include understanding the COUNTIFS function, as this was novel to me and took some time to understand. As well, I made some mistakes when inputting the correct data ranges in the COUNTIFS formula, but double-checking my work allowed me to resolve these mistakes.  

## Results

- Two conclusions you can draw about the Outcomes based on Launch Date: The line graph ![Outcomes_vs_Goals] (https://github.com/AaraniSivasekaram/Kickstarter-Analysis/commit/d4240ec0ff2e60b0e303e8ac5c592de1fe7c8123) visualizes the data in the form of Theatre Outcomes based on Launch Date and depicts May, June and July as months where theatre campaigns are most successful. Theatre activities are likely more successful during summer months when theatre activities are more popular. 

- Conclusion about the Outcomes based on Goals: The line graph ![Theatre_Outcomes_vs_Goals] (https://github.com/AaraniSivasekaram/Kickstarter-Analysis/commit/d4240ec0ff2e60b0e303e8ac5c592de1fe7c8123) visualizes the data in the form of Outcomes based on Goals and depicts campaign goals in ranges of: less than $1000 to $4999, and $35000 to $44999 as most successful. However, there is no clear trend line in terms of outcomes based on goals with this sample of data.

- Limitations of this dataset: The dataset included only theatre campaigns as the parent category and plays as a subcategory, these are small samples that are better to compare with Louise’s comparisons, however, this provides a limited view of all the Kickstarter campaign data. As well, we did not look at data from live campaigns. 

- Other possible tables and/or graphs that we could create: It would be informative to create additional tables and graphs to compare other parent categories based on launch date, to determine if monthly trends differ based on parent category of campaigns. As well, it would be interesting to compare outcomes based on goals for different subcategories with the theater parent category.
