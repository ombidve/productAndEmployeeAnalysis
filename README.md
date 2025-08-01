# Product And Employee Analysis of Coco Company
In this project we were given data of COCO chocolate company where our main objective was to find the performance of product types in various markets as well as to find the performance of the particular employee.
<img width="779" height="444" alt="coco_dash" src="https://github.com/user-attachments/assets/b6513c9f-6d97-44b3-b4fa-140ed76c1a9d" /> <br>


The dataset consists of the main data table which is also a FACT table of the dataset, it has information of the Sales Person who has managed to sale the particular product in the specific geography on particular date. This data table also tells us the amount, no of customers and no. of boxes delivered. The other three tables are DIMENSION tables: Product, Geo and Sales Person are relationship tables.


<img width="729" height="412" alt="chocolates3" src="https://github.com/user-attachments/assets/37b174df-9dd5-4e3c-9c7b-4d63422abbb6" /> <br>
This is the main dashboard which consists of one table, one slicer and two charts. The table gives us the tabular value of each chocolate product i.e the total revenue earned to the company, a sales person Barr Faughny's amount generation, his amount in percentage and the bar amount generated amoong the two chocolate categories i.e bar and bites. A slicer of all the Sales Person's name is displayed on the top of the table by which we can see the contibution of every employee's contribution in the total sales according to the various products. 
The  Sum of Amount by Product chart is a stacked column chart. It visually helps us see which of the company's products are doing well in the market and which are underperforming. This visualisation helps the company CXOs take decisions on the production and inventory management. If any product is very underperforming then the officials of the company can decide to discontinue the product lineup.
The Total Amount by Geography is a Pie chart. It shows the company's business in different countries. It helps the company decide which international market they should focus improving on and which market is the main source of revenue and should try to increase more business there. The percent and amount Data Label helps the CXOs make an appropriate decision for their growth.

<img width="739" height="419" alt="perf of emplyee" src="https://github.com/user-attachments/assets/0b427b4e-bccb-402c-830f-e987297e4bfc" /> <br>

This Dashboard has two table charts. The first one being the box shipment by particular sales person and also the amount generated by them by selling the no. of boxes. The target given to all employess was to generate a total sales of 2 million. In the tgt cmp v1 comlumn you can see yes/no for the sales persons if they have completed the target value. In the second tgt cmp v2 column it displays the same information just in the form of emoticons. A '👍' if they have manages to complete the target and a '😭😭' if they were not able to complete the given target.🎈
The second table tell us about the performace of the particular employee. If the total amount is greater than 2.5 M then '🎄🎄🎄', if the amount is greater than 2.25M but less than 2.5M than '🎄🎄', if the amount is greater than 2M but less than 2.25M then '🎄'. If the employee has failed to secure the target they'll be in the red zone '🎈'. 
These emoticons are used to graphically visualise their performance score.

To make this Dashboards, we have used many DAX functions to that have helped us to evaluate the product sales and employee performance. 

*This project can be used by college students to help them understand dashboards and DAX functions used in MS PowerBI*
