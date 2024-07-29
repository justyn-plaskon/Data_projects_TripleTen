# Shopify App Analysis
The Shopify App Analysis project involved utilizing Power BI to explore the Shopify dataset and uncover insights into the app landscape, reviews, and app reviews. Specific visualizations were created to identify trends within each category, providing actionable insights for business decision-making. Due to limitations in grading Power BI files, screenshots of the visualizations were submitted for evaluation.

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Part 1 Question 1](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part1Q1.png) | KPI card that counts the unique number of apps |
| 2 | [Part 1 Question 2](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/PART1Q2.png) |  Line chart with the sum of the review count on the Y-axis, and the lastmod date on the X-Axis |
| 3 | [Part 1 Question 3](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part1Q3.png) |  Scatterplot with the reviews_count on the X axis and the average rating on the Y axis |
| 4 | [Part 2 Question 1](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part2Q1.png) | A DAX expression calculated a "helpful_reviews" column in the "Reviews" table by multiplying "rating" by "(1+helpful_count)" to weight reviews, and a card visualized the average of this weighted score.|
| 5 | [Part 2 Question 2](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part2Q2.png) | Scatterplot comparing the average rating on the y-axis against a calculated "developer_answered" column  |
| 6 | [Part 3 Question 1](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part3Q1.png) | A bar chart was created displaying the sum of ratings on the y-axis for each developer on the x-axis.  |
| 6 | [Part 3 Question 2](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part3Q2.png) |  Bar chart displaying average "helpful_review" value per developer.  |
| 6 | [Part 3 Question 3](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Part3Q3.png) |  A filtered bar chart focused on developers with over 500 reviews, comparing them based on "developer_answered" to identify the most responsive. |
|  | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| | [Requirements.txt](URL HERE) | A simple .txt file with the provided project requirements as provided by TripleTen. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, including files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

### Data
DESCRIPTION HERE:
- `'apps'`: Details of the apps on Shopify apps marketplace
- `'apps_categories'`: contained app id and category id for joining
- `'categories'`: Categories of the apps. Each app has multiple categories
- `'reviews'`: Each review includes a user's rating, comment, and potentially a developer's response.
    - `'FIELD NAME'`: DESCRIPTION HERE
  
### Description:
- # 6 screenshots that answer a business question
- Screenshot of Power BI 

### Assumptions:
-The scraped data accurately represents the overall Shopify app landscape.
-The data is sufficiently clean and complete for analysis.
-App success can be accurately measured through metrics such as number of reviews, ratings, and downloads.
-The factors influencing app success are consistent across different app categories.
-The visualization choices made effectively represent the underlying data and insights.

### Process:
Each visual represents a set of questions. 
-Part 1 Question 1: A KPI card that counts the unique number of apps was created and added to the App Landscape sheet.
-Part 1 Question 2: A line chart with the sum of the review count on the Y-axis, and the lastmod date on the X-Axis was created
-Part 1 Question 3: A scatterplot with the reviews_count on the X axis and the average rating on the Y axis was made. An annoted interpretation of this with an inserted Text Box next to the scatterplot was required.
-Part 2 Question 1: A new column named "helpful_reviews" was created in the "Reviews" table using a DAX expression. This column multiplied the "rating" by "(1+helpful_count)" to weight reviews based on perceived helpfulness. A card was generated displaying the average value of the newly created "helpful_reviews" column.
-Part 2 Question 2: A new column titled "developer_answered" was created within the "Reviews" table using a DAX expression. This column assigned a value of 1 (or TRUE) if the "developer_reply" column was populated, and 0 (or FALSE) otherwise. A scatterplot was generated comparing the average rating on the y-axis against the "developer_answered" column on the x-axis.
-Part 3 Question 1: A new relationship was established between the "Reviews" and "Apps" tables using the "app_id" column as the common key. This relationship was configured as many-to-one, with multiple reviews associated with a single app. A bar chart was created displaying the sum of ratings on the y-axis for each developer on the x-axis. 
-Part 3 question 2: To address the potential bias of the previous bar chart, a new bar chart was generated. This chart displayed the average "helpful_review" value on the y-axis for each developer on the x-axis.
-Part 3 Question 3: A bar chart was created featuring the "developer" from the "apps" table and the "developer_answered" column generated in a previous step. A filter was applied to this visual, restricting the data to rows with a "reviews_count" exceeding 500 to identify the most responsive developers among those with a substantial review volume.


### Notes:
To facilitate evaluation, students were required to submit screenshots of their visualizations as a PowerBI file is too large to send. 



