# Cause of Returns at Superstore
The project leveraged the Superstore dataset to analyze return rates. A calculated field was implemented to isolate returned orders, facilitating subsequent analysis. Tableau visualizations were employed to identify return patterns across various dimensions. Key findings include a disproportionately high return rate for the tables product category, significantly impacting profitability. Binders were found to be the most returned sub-Category although impacting profitability less severly. A Dashboard and story presentation were created to explain findings to stakeholders.


### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Tableau File](https://public.tableau.com/app/profile/justyn.plaskon/viz/J_PLaskonSprint5Project/ReturnRatebyCustomer?publish=yes) | Tabelau file including dashbaord and story presentation.|
| 2 | [README.md](https://github.com/justyn-plaskon/Data_projects_TripleTen/edit/main/Cause%20of%20Returns%20at%20Superstore/Readme.md) |Project information and background.|
| 3 | [Requirements.txt](https://github.com/justyn-plaskon/Data_projects_TripleTen/blob/main/Cause%20of%20Returns%20at%20Superstore/Superstore.requirements.txt) | Requirements of this analysis.|

| DATA | Describes the source of data, including files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

### Data
DESCRIPTION HERE:
- `'Superstore.xls'`: Each row corresponds to one product sold; sheets were LEFT JOIN'd
    - `'orders'`: details all fields for each ordered item.
    - `'returns'`: details all fields for each returned item.
  
### Description:
- 18 page Tableau Visualization and presentation.
- Includes story presenting findings, dashboard and data analysis.

### Assumptions:
- Profits are in the negative.
- Negative profits are directly linked to issues with orders and high number of returns.
- Changes based on data driven recommendations are needed to prevent bankruptcy.

### Process:
-The sheets were initially joined. Subsequently, data was analyzed using visualizations to identify the root causes of returns. A dashboard was then constructed for return monitoring. Finally, a Tableau story was created to present the findings.


### Findings:
-Binders are the most returned subcategory overall. 
-Tables are the most returned sub category earning a negative profit
-Certain subcategories such as binders and paper have a large amount of items with over double the average return rate. 
-There is a seasonality to the sales and return cycle

### Recommendations:
-Investigate why binders and paper are so often returned and make sure to elimate an errors in the listings of these items
-Make tables a special order item, and have sales people guide custoimers toward the correct table.
-Steer customers troward buying less returned items by placing the least returned items higher in the superstore websearch

### Notes:
Mockup dashboard was a project requirement


 
