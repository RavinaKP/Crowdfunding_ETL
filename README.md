
 --PROJECT 2 CROWFUNDING_ETL-- 
==================================

# Objective: 
Building an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform the data. After transforming the data, ywe created four CSV files and used the CSV files data to create an ERD and a table schema. Finally,  uploaded the CSV file data into a Postgres database

# Transforming data code:

Link yo code: Starter_Files/Starter_Files/ETL_Mini_Project_DPitchikala_RKolsawala_Code.ipynb

# Database Loading:

Step 1: After inspecting the csv files from the previous Analysis, created an ERD using QUICKDBD tool:

![image](https://github.com/RavinaKP/Crowdfunding_ETL/assets/77449446/550e64ed-1bbd-40b4-b153-2beadd81c8b7)

Step 2: To create schema Crowdfunding_db_schema.sql using the above diagram as refernce

Step 3: Create a new Postgres database, named crowdfunding_db

Step 4: upload the csv files using the schema created

Step 5: Test if the data is loaded correctly:
      Table 1: using select statement dispaly the table "Campaign"

      ![image](https://github.com/RavinaKP/Crowdfunding_ETL/assets/77449446/a2f1e4d8-7081-4380-8008-ff0b032c18ca)

      Table 2: Table "Contacts"

      ![image](https://github.com/RavinaKP/Crowdfunding_ETL/assets/77449446/83a94496-61f7-4635-9c42-94137e53b3ac)

      Table 3: Table "Category"

      ![image](https://github.com/RavinaKP/Crowdfunding_ETL/assets/77449446/c15d0c8a-1f5b-4886-a67c-1b6ab87ce1c4)

      Table 4: Table "SubCategory"

      ![image](https://github.com/RavinaKP/Crowdfunding_ETL/assets/77449446/590108c7-6e7d-442e-a693-470c3c1a533c)


      




      



