Recruitment task for Ryanair.
Contains PBI file with the report as well as source files for dimensions and fact table. 

Dimension tables: 
Dim_Users: contains information about products users. 
Dim_Products: contains detailed information about the products. 
Dim_Date: calculated table added directly in PBI fie using CALENDARAUTO() function. Contains information about dates.

Fact table:
Fact_Sales: contains information about sales of new products, such as price, discount, units. Fact table was created in Power Query by combining 2 source files from the folder. 

Additionally, .pbix file contains calculated measures table, which contains all the DAX measures used in the report and groups them into 2 folders: 'Common measures' (common for the whole report) and 'New Products Overview' (specific only for this report page). 

