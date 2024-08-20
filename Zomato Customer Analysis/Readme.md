# Zomato Customer Analysis
This project analyzed spending patterns among Zomato customers to inform marketing and retention strategies. Customer data was segmented by demographics and spending habits, and visualized in interactive dashboards.

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zomato Customer Analysis](https://public.tableau.com/app/profile/justyn.plaskon/viz/J_PLASKON_ZomatoCustomerAnalysisFinalProject/ZomatoDash?publish=yes) | This project explored the spending habits of Zomato customers across various demographic segments. By filtering the educational qualifications dashboard to exclude 'uneducated' and 'school' levels, spending trends for higher education groups became more apparent in the spending by month per education graph. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Zomato%20Customer%20Analysis/Zomato.requirements.txt) | Required to clean the data appropriately using the dataset provided by TripleTen |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, including files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

### Data
TripleTen provided a file of 5 separate Excel files from the mock company Zomato. Two were used for this project.
- `'Orders'`: All orders made by all customers at all restaurants between Oct. 4th, 2017, and June 26th, 2020
    - `'order_date'`: Date order was placed
    - `'Sales_qty'`: Number of items on per order
    - `'sales_amount'`: numerical value of order in 1 of 2 currencies
    - `'currency'`: The currency used
    - `'user_id'`: unique ID for each user: used to join tables
    - `'r_id'`: Unique ID for each restaraunt
- `'Users'`: Demographic data for all customers who placed orders within the specified period.
    - `'user_id'`: unique ID for each user: used to join tables
    - `'name'`: first and last name of each user
    - `'Age'`: Age of each User
    - `'Gender'`: Gender of Each User
    - `'Marital_status'`: Marital Staus of each user divided into single, married or prefer not to say
    - `'Education Level'`: The Education level of each user sorted into: Graduate, Ph.D, Post Graduate, School and Uneducated
    - `'Occupation'`: The Ocupation of eaach user sorted into: Student, Employee, House wife, and Self Employed
### Description:
- Tableau Work Book, 1 Dashboard to present the findings, 1 Story presentation, 2 dashboards to include in the story, 12 Charts
- Customer Segmentation Analysis
  

### Assumptions:
-The provided datasets are considered accurate, complete, and consistent for this analysis. 
-Minor data quality issues are present but deemed inconsequential. 
-The data is well-structured, with clear column definitions

### Process:
-Data was analyzed and initial findings were submitted along with a plan. Once this was approved the data wasd more fully analyzed and visuals were created. Findings were presented with a Dashboard and story presentation


### Findings:
-Single students represented the largest customer segment, while spending tended to decrease with age.

### Recommendations:
- To optimize marketing efforts, focus on retaining existing customers as they age and explore opportunities to attract older demographics. Additionally, leverage the substantial single-student customer base to drive sales.

### Notes:
Submitting my initial analysis and plan was a project requirement

