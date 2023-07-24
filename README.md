# Crowdfunding_ETL
### Group Members:
- Daniel Wallach
- Mohamed Aamer
- Nestor Baptista
---
The ETL Project is designed  to gain hands-on experience in building an ETL (Extract, Transform, Load) pipeline. The project focuses on working with Excel data and involves extracting data from Excel files, transforming it using Python and Pandas, creating CSV files, designing an ERD (Entity-Relationship Diagram), creating a table schema, and loading the data into a Postgres database.

## Data Extraction:

Data will be extracted from two Excel files: crowdfunding.xlsx and contacts.xlsx. The crowdfunding.xlsx file contains data related to campaigns, categories, and subcategories. The contacts.xlsx file contains data related to contact information.

## Data Transformation:

Python and Pandas will be used to transform the extracted data into meaningful and structured formats. The transformation includes tasks such as renaming columns, converting data types, cleaning data, and splitting information.

## CSV File Creation:

After data transformation, four CSV files will be created as intermediate outputs:
category.csv: Contains the category DataFrame.
subcategory.csv: Contains the subcategory DataFrame.
campaign.csv: Contains the campaign DataFrame.
contacts.csv: Contains the contacts DataFrame.

## Entity-Relationship Diagram (ERD) Design:

An ERD will be sketched based on the relationships between different tables and entities in the project. The ERD will provide a visual representation of the database structure.

## Table Schema Creation:

Based on the ERD, a table schema will be designed for each CSV file. This includes defining data types, primary keys, foreign keys, and other constraints.
Postgres Database Setup:

A new Postgres database named "crowdfunding_db" will be created to store the transformed data.
Table Creation and Data Loading:

Using the table schema, tables will be created in the "crowdfunding_db" database in the correct order to handle foreign keys.
The data from the CSV files will be imported into their corresponding SQL tables.
Data Verification:

SELECT statements will be executed to verify that the data in the database tables matches the transformed data from the CSV files.

### Crowdfunding Database ERD
![crowdfunding_db_schema](https://github.com/MAamer28/Crowdfunding_ETL/assets/130619866/66f2f10b-934b-4c94-942d-a70f910b4ccc)

### Table 1: Campaign
<img width="2672" alt="CrowdfundingDB_Campaign" src="https://github.com/MAamer28/Crowdfunding_ETL/assets/130619866/71637850-a707-431d-88c4-5f6e1b6fb571">

### Table 2: Categories
<img width="2672" alt="CrowdfundingDB_Category" src="https://github.com/MAamer28/Crowdfunding_ETL/assets/130619866/c3642ee8-b11c-4d8d-90b8-0b5ba92af042">

### Table 3: Subcategories
<img width="2672" alt="CrowdfundingDB_Subcategory" src="https://github.com/MAamer28/Crowdfunding_ETL/assets/130619866/c9aade3a-1c78-4a14-bd7c-a09fbdd9785f">

### Table 4: Contacts
<img width="2672" alt="CrowdfundingDB_Contacts" src="https://github.com/MAamer28/Crowdfunding_ETL/assets/130619866/0182ed48-fcb5-4ac7-bc56-ad06408f8d43">

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
