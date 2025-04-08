# Harbor Freight Product Recommendation System

**Overview**
- This project was completed as part of the MIS 531 course at the University of Arizona, focusing on applying Enterprise Data Management (EDM) principles to solve real-world business data challenges. 
- The student team '200 OK' designed and developed a cloud-based database solution tailored to improve operational efficiency, reporting, and decision-making.

**Technologies Used**
- **Backend:** Oracle Database, SQL
- **Frontend:** HTML, JavaScript, PHP
- **Tools:** Microsoft Visio, AWS EC2, SQL Developer

**Features**
- Visio-based ERD and normalization diagrams
- Oracle SQL scripts for table creation and complex queries
- Frontend interface for product display and interaction
- Dynamic product recommendation engine
- Cloud-based deployment using AWS EC2

**SQL Queries Implemented**

1. Display a prompt to the customer when only 5 or less than 5 items are available for a particular product
2. Display the top 3 frequently bought together items for a product
3. Display the top deals on the best selling products
4. Display the top selling products in a season
5. Display that the shipping is free when a customer is ordering an item that is present in a store that is in the same locality of the customers
6. Display the average ratings for Products
7. Display the total money saved by a customer through deals and coupons
8. Display the average turn around time of the agent assigned to a customer's ticket
9. Update customer address
10. Delete customer address
11. Change the wording on the gift cards page to 'Paste your gift card details to activate the gift card'

**Triggers Implemented **

1. Update wallet balance in Customers table
2. Update numberOfTickets in Agents table

**Stored Procedures Implemented**

1. Assign agent to a customer query. Agents with lowest open tickets will be assigned. High priority queries will receive the quickest resolving agents. 
