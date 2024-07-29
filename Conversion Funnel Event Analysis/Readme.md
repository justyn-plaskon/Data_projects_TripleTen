# Conversion Funnel Event Analysis

This project analyzed user behavior to understand the conversion and retention rates on a platform. By constructing a conversion funnel and conducting cohort analysis, the project identified a significant decline in user retention after the initial month. To address this, the project recommends focusing marketing efforts on newer user cohorts to improve overall platform retention.

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Conversion Funnel Project Spreadsheet](https://docs.google.com/spreadsheets/d/1nMU8deU6D3NWAMTT_YxQYB-urH9R5wNNm05VM2ZIjg4/edit?gid=38637670#gid=38637670) | Completed Spreadsheet, including pivot tables and calcukayted feilds to support findings |
| 2 | [Raw Data](https://docs.google.com/spreadsheets/d/1yuavBZ4OYYUD1opH-dq0d6nejREDy8f0ozumT9-yEuo/edit?gid=0#gid=0) | Data File Provided by TripleTen |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](URL HERE) | A simple .txt file with the provided project requirements as provided by TripleTen. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, including files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

### Data
DESCRIPTION HERE:
- `'raw_user_activity'`: Table containing the raw user data for all web events
    - `'user_id'`: unique id assigned to every user
    - `'event_type'`: action user took, seperated into "view", "shopping_cart" and "purchase"
    - `'event_date'`: date of the event
    - - `'first_purchase'`: calculated feield based on the first purchase date for each user_id. Used to form cohorts 
  
### Description:
- # 8 Sheet Google Sheets doc
-Includes table of contents, Executive Summary, Conversion Funnel calculated based on purchase activity, cohort analysis using the first purchase date to seperate users into cohorts, retention rates using the cohorts, first purchase table and raw data

### Assumptions:
-The provided "raw_user_activity" dataset is considered complete and reliable for the specified time period. Data quality issues, such as missing values or inconsistencies, are negligible and can be disregarded. Additionally, the data is structured correctly, with consistent column formats and data types.

### Process:
-Initial data exploration, cleaning, and filtering were conducted. Subsequently, a conversion funnel was constructed and data was prepared for cohort analysis. Retention rates were calculated, followed by final report formatting and documentation for optimal client comprehension.



### Findings:
-For the Conversion Funnel Average CTR was 27% and average CR is 41%
-The cohort analysis showed the first cohort has the highest retention. Retention drops significantly between months 2 and 3 

### Recommendations:
- Focus marketing on newer cohorts to increase retention. 

### Notes:
