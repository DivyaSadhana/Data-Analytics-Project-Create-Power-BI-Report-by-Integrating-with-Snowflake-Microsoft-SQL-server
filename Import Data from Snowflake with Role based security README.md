A. Requirements:
1. On Power BI, 'Import' Data from Snowflake Cloud with Role based security.

B. Pre-Requisites:
1. Download and install Snowflake ODBC server to estbalish connection between Snowflake account and Power BI Desktop. 
<img width="597" height="422" alt="image" src="https://github.com/user-attachments/assets/fb56755e-3fe0-4ee5-856e-aab800077d34" />

2. Identify whether Windows Snowflake ODBC installed was either 32-bit or 64-bit Data Source. Then add it on System DSN.
<img width="593" height="416" alt="image" src="https://github.com/user-attachments/assets/4c22d7c5-e6e3-4234-89e4-9e02ba054559" />


C. Implementation Tasks:
1. Connect Snowflake on Get Data.
<img width="1840" height="1054" alt="image" src="https://github.com/user-attachments/assets/f50ba155-4783-4d36-8df5-c1350fe81ac2" />


2. Add Server Name, Warehouse Name, Database Name.
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/740cacf1-41e3-4ba5-857c-73525c8795b3" />


3. Add User Name and Password. Business_Analyst_US is the user name.
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/801635a4-6709-4bfb-ae90-c937668bcb62" />

4. The user is able to view Hospital Dataset schema and Patient_Analytics_US schema only. Select required data table and Load it. 
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/acaf6091-62ff-4d56-b4b7-1acc270785c7" />

5. Select Import Data.
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7f79d244-5620-4a69-b18e-dddc16151007" />

6. Verfy the loaded data on a table.
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60022b9d-006c-4d7e-ab95-69bf1958ddd1" />




