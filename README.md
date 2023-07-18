# business_analysis
- A new restaurant owner has requested a database creation where they can track their orders for their restaurant. 
- First I used QuickDBD to organize the first version of the table
- My original table creation had a lot of redundancy, so I normalized the data to improve efficiency and reduce redundancy by creating additional tables for the deliveries and the customers.
- I created separate tables for customers and addresses, and an item table in case there are any changes to the menu in the future. This way only one smaller table will need to be adjusted.
- The owner would like to keep track of inventory to know when stock orders need to take place. To do this we need to know what ingredients go into which pizza, how much stock he has left, and the quantity of each ingredient based on the size of the pizza. For simplicity I assume that all delivery suppliers come at the same time.
- The owner also wants staff data to know when employees are working, and based on the staff salary information, how much each pizza costs (ingredients+chefs+delivery)
