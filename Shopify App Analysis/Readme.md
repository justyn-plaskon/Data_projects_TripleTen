This project utilized Power BI to analyze the Shopify app landscape, reviews, and app reviews to gain valuable business insights.

The project focused on three key areas: App Landscape, Reviews, and App Reviews. For each section, specific Power BI visuals were created to showcase trends. KPIs, line charts, scatterplots, and custom DAX expressions were used to analyze data and answer specific business questions. The final visuals were captured as screenshots and submitted for review.

App Landscape:
KPI Card: This visual displayed a single number representing the total count of unique apps available on the Shopify platform. 
Line Chart: This chart tracked the volume of app reviews over time, with the sum of the review count on the Y-axis and the last modified date (indicating review activity) on the X-axis. 
Scatterplot with Text Box: This visualization explored the relationship between the number of reviews (reviews_count) and the average rating for each app. A text box with an annotation was included to interpret the findings, highlighting any trends or insights observed. 
Reviews:
Calculated Field: A custom DAX expression was created to calculate a "helpful_reviews" score. This score multiplied the individual review rating by (1 + helpful_count), giving more weight to reviews marked as helpful by users.
Card with Average Helpful Reviews: This visual displayed the average value of the newly created "helpful_reviews" column, providing an overall sense of user sentiment towards app reviews. 
Scatterplot with Developer Answered: This chart compared the average rating (Y-axis) with a new "developer_answered" column created using another DAX expression. This column indicated whether the developer responded to the review (Yes/No). 
App Reviews:
Relationship Building: A new relationship was established between the "Reviews" and "Apps" tables in the Power BI data model. This linked reviews to their corresponding apps using the "app_id" and "id" columns, enabling analysis by developer.
Bar Chart by Developer: This visual displayed a bar chart with developers on the X-axis and the sum of their app ratings on the Y-axis. This provided a high-level overview of app performance based on developer. 
Bar Chart with Helpful Reviews: Recognizing the potential for misleading information in the previous chart (apps with many low ratings could inflate the sum), a new bar chart was created. This chart focused on the average "helpful_reviews" score for each developer, offering a more nuanced view of user sentiment. 
Bar Chart with Developer Responsiveness: This chart displayed a bar chart with developers on the X-axis and a count of "Yes" responses in the "developer_answered" column. A filter was applied to only include apps with over 500 reviews, ensuring a more reliable representation of developer responsiveness for established apps. 
By analyzing these various visuals and the underlying data, the project aimed to provide comprehensive insights into the Shopify app landscape, user reviews, and developer engagement.
