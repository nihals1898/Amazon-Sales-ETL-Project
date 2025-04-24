Amazon Sales ETL & Data Warehouse – README

Step 1: Create Database & Schemas -> Run Create-DB&Schemas script which is under DbScript folder.

Step 2: Run the .sln file that is provided in the base folder.  

Step 3: Update Connection Managers
-> Open the SSIS Package.
-> In the Connection Managers pane at the bottom, locate: CM_OLEDB_AmazonSales. Right click ---> Edit and Update the Server Name and ensure that Initial Catalog = AmazonSales
-> In the Connection Managers pane at the bottom, locate: SalesData_ExcelConnection. Ensure that the file path is pointing to the Amazon Sale Report.xlxs which is inside the Data folder.

Step 4: All good to go, just execute the Pipline.

Cheers!!!!!!!
