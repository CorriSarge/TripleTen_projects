# File Title: SuperStore Returns

This was my fifth project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Tableau Story Telling.

Video Presentation: <a href='https://youtu.be/uiNIs_U2BLg' target=_blank><u>here</u>.</a>
Full Project on Tableau: <a href='https://public.tableau.com/app/profile/corrinne.sargent/viz/SuperstoreReturns_17120137434790/ReturnMetrics' target=_blank><u>here</u>.</a> 

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [DataSet - SuperStore.xls](https://github.com/CorriSarge/TripleTen_projects/blob/main/SuperStore%20Returns/Sample%20-%20Superstore.xls) | The original data file provided by TripleTen that was used in this projects analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/CorriSarge/TripleTen_projects/blob/main/SuperStore%20Returns/Requirements) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Reviewer Grade.png](https://github.com/CorriSarge/TripleTen_projects/blob/main/SuperStore%20Returns/Returns%20reviewer%20comments.png) | This is the comments left by my project reviewer. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final products purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Excel spreadsheet file provided by TripleTen:
- `'Superstore.xls'`: each row corresponds to one product sold; sheets were LEFT JOIN'd
    - `'orders'`: details all fields for each ordered item
    - `'returns'`: details all fields for each returned item

### Description:
- 9 charts, 5 dashboards and 1 presentation on Tableau
- Includes data analysis, charts, dashboard, and stories
- Purpose was to prepare an analysis for the CEO of Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders

### Assumptions:
- Profits from sales are totaling in the negative.	
- There is one or more causes for negative profits directly related to orders and returns.
- Operations department will need to make changes.

### Process:
I first joined sheets.
Then I analyzed data using visualizations to determine what is causing returns.
I built a dashboard for monitoring returns.
Lastly I created Tableau story to present my finding.

### Findings:
1. Returned purchases are the leading cause of declining profits at Superstore.
2. There is a positive correlation between sales and returns.
3. The technology category has the largest return rate.
4. There are several customers who have a return rate of 100%.
5. Each state had different rates of return for different sub-categories.
6. Orders made throughout the year had higher return rates depending on the month.
7. Return rates do not correlate with the amount of product sold, some of the lowest selling products had a return rate of 100%.
