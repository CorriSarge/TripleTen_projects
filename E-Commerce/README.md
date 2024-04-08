# File Title: Business Analysis

This was my third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Business Analytics.

Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1LQ3TEBxs24to6wiLHhIr9kuY17iKpefGKQPzkk7MKHw/edit#gid=38637670' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Business Analytics Project.xlsx](https://github.com/CorriSarge/TripleTen_projects/blob/main/E-Commerce/Business%20Analytics%20Project.xlsx) | The original data file provided by TripleTen that was used in this projects analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/CorriSarge/TripleTen_projects/blob/main/E-Commerce/Requirements) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Reviewer Comments Sprint 3.png](https://github.com/CorriSarge/TripleTen_projects/blob/main/E-Commerce/Reviewer%20Comments%20Sprint%203.png) | This is the comments left by my project reviewer, number corresponds with project number. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final products purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

### Description:
- 8 page spreadsheet
- Includes raw data, processed data, data analysis, and pivot tables.
- Purpose was to analyze the companys' raw transaction logs and turn the event logs into business metrics.

### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

### Process:
I first explored, filtered, and cleaned the data.
Then I created built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly I finalized formatting and documentation for the client's readability.

### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 
