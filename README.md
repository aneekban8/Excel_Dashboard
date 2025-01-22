# Excel_Dashboard
Excel Dashboard.
In the 'Data' sheet of the file 'Excel Dashboard2 4 charts.xlsx', data on the sales made by different salespersons in different years (2004,2005,2006,2020,2021,2022, 2023), for 5 different products (eyeliner, mascara, lip gloss, lipstick, foundation) are given. Different salespersons are present in different years. In the sheet 'Sheet1', depedent dropdown lists are used to compare the sales made by 2 salespersons, in a particular quarter of a particular year for a particular product. First, the year is chosen in Cell B3 of 'Sheet1'. Next, the quarter is chosen in cell F3. Next, name of salesperson 1 is chosen in cell B7. Next, name of salesperson 2 is chosen in cell F7. Next, the product is chosen in cell K7. Then the 4 charts given in 'Sheet1' will automatically update. Please scroll the sheet if the charts do not appear to be updating. The clustered column graph in the top left chart shows a comparison of the growth rates in sales (for the chosen product) achieved by the 2 salespersons in the current quarter and preceding 2 quarters. The line graphs in the top left chart show the absolute sales figures (for the chosen product) of the 2 salespersons in the current quarter and the preceding 2 quarters. The pie chart (in the top right) shows the shares of each of the 5 prodcuts in total sales made by salesperson 1 in the current quarter (chosen quarter). The pie chart (in the bottom right) shows the shares of each of the 5 prodcuts in total sales made by salesperson 2 in the current quarter (chosen quarter). The pie chart in the bottom left shows the shares of each of the salespersons, in the total sales of the chosen product, in the current (chosen) quarter.
The same data is present in the 'Data' sheet of the file 'Excel Dashboard 200125 V10.xlsm'. This file contains 3 VBA macros: chk_data, enlarge_X, cr_chart. The first macro checks the condition that for newly added data, every seller must sell every product in each quarter. If data for a particular seller and a particular product is missing for a particular quarter (in newly added data), the macro will give the message "Data for 'this' seller for 'this' product is missing for 'this' quarter". Otherwise the macro will give the message "Data quality is OK". The first macro is run by clicking the first Command Button from left in 'Sheet1'. The second macro expands the lookup tables used for the dependent dropdown lists. Before running the second macro, delete the values in range AA1:AD7 in 'Lookup_Sheet1' and the values in range 'CH1:CH5' in 'Sheet1'. The second macro is run by clicking the second Command Button from left in 'Sheet1'. The third macro creates the same 4 charts as in 'Sheet1' of the file 'Excel Dashboard2 4 charts.xlsx'.
The third macro is run by clicking the third Command Button from left in 'Sheet1' of the file 'Excel Dashboard 200125 V10.xlsm'.
