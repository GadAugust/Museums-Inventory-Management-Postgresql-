# Museums-Inventory-Management-Postgresql-

The Heritage Museums Case Study, implemented with PostgresSQL, aims to address the operational challenges faced by a chain of heritage museums spread across various countries. 

The project focuses on mastering Data Definition Language (DDL) and Data Manipulation Language (DML) queries to optimize museum operations and inventory management.

# Business Problem:

 Heritage Museums manages a network of museums worldwide, each housing unique collections of paintings that attract visitors globally. However, decentralized management across diverse locations hinders efficient operations and inventory oversight. The absence of centralized visibility complicates decision-making and operational efficiency.
 
# Business Questions to Address:

- Identify Museums without any paintings.
- Retrieve paintings not displayed in any museum.
- Determine Museums open every single day.
- Identify Museums with invalid city information and update them.
- Calculate the average price of artworks in each museum.
- Find the museum with the longest opening hours on Fridays.


# Objective: 

The primary objective of the project is to develop SQL queries that provide insights into museum operations and inventory management. By addressing key business questions, the project aims to optimize decision-making processes and enhance operational efficiency across the museum network.

# Key Features:

- Implementation of DDL and DML queries in PostgresSQL.
- Exploration of museum data to derive meaningful insights.
- Development of SQL queries to address specific business questions.
- Identification and resolution of data inconsistencies and errors.
- Analysis of museum opening hours and artwork pricing.


# The Dataset:

- Museums: Contains information about all the museums in the chain

- Artists: Stores details about various artists whose works are displayed in the museums

- Museum Hours: Specifies the working hours of each museum, categorized by the 
days of the week

- Artworks: Includes information about all the artwork displayed in the museums

- Product_sizes: Provides available sizes and the prices for each artwork


# Expected Outcome: 

The project is expected to deliver a set of SQL queries capable of addressing the identified business questions effectively. By leveraging SQL capabilities, the project aims to streamline museum operations, improve inventory management, and facilitate informed decision-making processes.

# Database Environment Setup:
![image](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/f09f82c1-d803-45b1-b8bd-952b46235446)

![WhatsApp Image 2024-02-01 at 00 29 10](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/02bb6ac9-bc1e-44f5-abeb-b23699a0db06)

![WhatsApp Image 2024-02-01 at 00 31 29](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/8720d95e-c0f2-48c6-9c6b-581f4ce3c43c)

# Created Table:

![WhatsApp Image 2024-02-01 at 00 47 14](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/af9cad38-b368-47af-8b8f-d6120025f1b8)

# Exploratory data analysis (EDA)

To ensure data integrity and consistency during the import process:
I had to clean the data by removing duplicate entries in a column, esp. where the the duplicate entries were just a few, but for other tables that had countless duplicates entries, I created a tmp_table of that table without a primary key using this type of querries below:

![Screenshot 2024-02-01 at 23 22 16](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/6e7736d4-fa9c-4d49-825a-b91cde30b103)

# Populated data view:
![Screenshot 2024-02-01 at 23 26 51](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/77092bfa-5534-43b7-8b1b-d6654b50f69f)


![Screenshot 2024-02-01 at 23 28 56](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/152d0749-6f8b-42a6-8c98-69bbe9a36357)

![Screenshot 2024-02-01 at 23 32 13](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/4728c090-999b-4ca0-a49e-c1eb7102fb20)

![Screenshot 2024-02-01 at 23 33 56](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/437d1b60-9fa5-41ed-a2ea-4eacb5251752)

# Data Control: creation of user inventory_manager:

![Screenshot 2024-02-01 at 23 38 26](https://github.com/GadAugust/Museums-Inventory-Management-Postgresql-/assets/81167692/17d30446-0c32-4a30-b17f-06a674f3d509)



