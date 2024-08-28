![logo](https://github.com/user-attachments/assets/60d92458-c79a-4968-bacc-ca2840627291)

# Western Digital Sales Data Mart -  BI Project
Final Project in BI Systems Development course at Experis Academy.

This project is dedicated to crafting a comprehensive BI solution created for Western Digital's sales department, featuring a data mart and reports developed in Power BI.

## Project Overview
### Project Specifications:
Planning the data mart and reports, including crafting essential documents such as the [ERD](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/ERD.png) and [Source-to-Target Mapping](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/S2T%20Mapping.xlsx).

These artifacts provided the foundational blueprint for subsequent development phases.

### Data Mart Development: 
SSIS is used for the ETL process to load OLTP data from the PriorityERP database, transform it, and load it to the final Data Mart tables.
Data quality assurance tests were conducted throughout this process to maintain data integrity. 
The resulting data mart comprises 1 fact table, 4 dimension tables, and 2 history tables.

### Power BI Reports:
This phase involved creating additional tables, calculated columns, and measures using DAX to support the envisioned visualizations and, subsequently, proceeding to craft and design the visualizations.
1 Executive Dashboard and 2 Reports were created: Sales Analysis and a Customers Analysis.

## Repository Contents
* [Western Digital Sales DM - BI System Specifications Document.pdf](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/Western%20Digital%20BI%20Project.pdf): Detailed project specifications.

* [ERD.PNG](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/ERD.png): Visual representation of the database schema, illustrating entity relationships.

* [S2T Mapping.xlsx](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/S2T%20Mapping.xlsx): Document detailing the transformation and loading process of source system data into the data mart.

* [Gantt.pdf](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/Gantt.pdf): Timeline representation showcasing project milestones and schedules.

* [Dashboard.pbix](https://github.com/TA-CodeProjects/Western-Digital-BI-Project/blob/main/Dashboard.pbix): The Power BI file containing the developed reports and visualizations.
