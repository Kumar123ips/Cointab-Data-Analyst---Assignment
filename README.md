# Cointab-Data-Analyst---Assignment
Overview
This repository contains the code and results for the Data Analyst assignment for Cointab Software Private Limited. The assignment involves analyzing data from an ecommerce company (referred to as X) to verify the charges levied by their delivery partners.

Business Scenario
As a data analyst, your task is to examine the charges imposed by courier companies per order and validate their correctness. The charges are dependent on the weight of the product and the distance between the warehouse and the customer's delivery address. The goal is to compare the charges reported by X with those billed by the courier companies.

Input Data
Left Hand Side (LHS) Data
Website order report

Lists Order IDs and various products (SKUs) in each order.
Warehouse pincode to All India pincode mapping

Used to determine the delivery zone during analysis.
SKU master with gross weight

Contains the gross weight of each product for calculating the total weight of each order.
Right Hand Side (RHS) Data
Courier company invoice in CSV file

Includes AWB Number, Order ID, weight of shipment, warehouse pickup pincode, customer delivery pincode, zone of delivery, charges per shipment, and type of shipment.
Courier charges rate card

Specifies charges at weight slab and pincode level.
Output Data
Output Data 1 (CSV/Excel file)
Columns:
Order ID
AWB Number
Total weight as per X (KG)
Weight slab as per X (KG)
Total weight as per Courier Company (KG)
Weight slab charged by Courier Company (KG)
Delivery Zone as per X
Delivery Zone charged by Courier Company
Expected Charge as per X (Rs.)
Charges Billed by Courier Company (Rs.)
Difference Between Expected Charges and Billed Charges (Rs.)
Output Data 2 (Summary Table)
Columns:
Total orders where X has been correctly charged
Total invoice amount for correctly charged orders
Total orders where X has been overcharged
Total overcharging amount
Total orders where X has been undercharged
Total undercharging amount
Assignment Data Download
Please download the assignment data from the following link: Assignment Data

Submission
Submit the result in an Excel file with two workbooks (summary table in one and order-level calculation in another) and your code in any programming language such as Python, R, Java, JavaScript, etc. Zip the files and share them at "work-data-analyst-1-v1@cointab.net".

This README provides a clear outline of the assignment, the input and output data formats, and instructions for submission. Feel free to customize it further based on your specific requirements.






