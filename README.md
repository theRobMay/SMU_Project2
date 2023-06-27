# SMU_Project2
The core concept of this project was to create a ETL pipeline so to accomplish this we have created 3 jupyter notebooks, their purposes have been outlined below. The schema used to create the tables in postgres can be found in the SQL & ERD folder.

- The first notebook is the Extration notebook, in this we brought in 2 xlxs files from the resources folder and cleaned the data resulting in 4 new csv files that were then placed back in the resources folder.
- The second is a workbook which takes these new csv files and puts them into a data frame which is then loaded into our schema in postgres SQL using SQL alchemy.
- The third is a workbook which then pulls down the information from our locally hosted postgres SQL and querys it to plot a graph, in this case displaying the most popular catagory of crowdfunded project by total backer count.

-Rob & Raj 2023
