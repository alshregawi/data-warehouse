# data-warehouse
IMPLEMENTATION OF MEDICAL DATA, DATABASE DIMENSIONAL MODELLING, VISUALIZATION, XML AND NEO4J 
# Summary
the goal of this project is to design a suitable data warehouse for a healthcare provider. The provisional design is done by using lucidchart and the implementation and the ETL process was done using visual studio as well as the SSRS reports there is 4 dimension tables and 2 fact tables. I generated 8 reports in total 4 excel reports using SSRS and 4 visualisation reports using R studio. And then I used NEO4J to develop show the relationship between claims, invoices and services by using sample from the data. 
# Data source
It’s a medical database used for sending online claims from healthcare provider to insurance company using waseele E-claims system that’s provided by waseel company 
# Stakeholders identify key
 Stake holders are the managers of the healthcare provider and in order to keep their business successful and improve this business they have to calculate which doctors and which policies has the most revenue to the business, so they can decide to renew the contracts or not and rise the doctor’s salaries.
 # The goals of the DW 
 is to generate reports (excel and visual) that will help the stakeholders taking their decision and to help the healthcare provider to have accurate patient E-file record that has all the general information of the patients. And it will help the doctors to know which diagnosis and which main symptoms are the most common. The medical data can be studied to know what the causes of the illness is and why.
# The design
 I’m using galaxy schema design because we have two fact tables connected to the dimension tables to cover the most aspects of the medical data:
1-medical data (Diagnosis dimension)
2-customers (Patients) record (Patient fact table)
3-insurance data (Policy dimension)
4-financial data (policy fact)
