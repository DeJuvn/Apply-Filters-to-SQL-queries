# Apply-Filters-to-SQL-queries
<!-- This Project was done in my Google Cybersecurity training -->

<b>Project description</b>

My role in the organization involves guaranteeing the safety of the system by identifying potential security risks and updating employee computers as necessary. To achieve these security-related objectives, I utilize SQL queries with filters, and the following examples illustrate the steps I take using SQL.


<b>Retrieve after hours failed login attempts</b>

In response to a security incident that took place after business hours (after 18:00), all failed login attempts during that time require investigation. To filter for these attempts, I created a SQL query, the code for which is presented below.

![image](https://user-images.githubusercontent.com/131769679/236780856-e1fe303a-f207-4f5b-89f1-f1735e1c11e4.png)


<b>Retrieve login attempts on specific dates</b>

To investigate any login activity that occurred on 2022-05-09 or the day before due to a suspicious event, I utilized SQL query creation. The following code demonstrates how I filtered for these login attempts.

![image](https://user-images.githubusercontent.com/131769679/236781348-717d9891-bbe9-464e-8b93-ec80b4eeadf0.png)

<b>Retrieve login attempts outside of Mexico</b>

Based on my investigation of the organization's login attempts data, I suspect that there is an issue with login attempts outside of Mexico. As such, it is necessary to investigate these attempts. To filter for login attempts that occurred outside of Mexico, I created a SQL query, the code of which is demonstrated below.

![image](https://user-images.githubusercontent.com/131769679/236782025-91a59700-6ff6-4046-b89e-89c6fff35306.png)

<b>Retrieve employees in Marketing</b>

Updating the computers of specific employees in the Marketing department requires identifying which employee machines to update. To filter for employee machines from employees in the Marketing department in the East building, I utilized SQL query creation, as demonstrated in the following code.

![image](https://user-images.githubusercontent.com/131769679/236782192-0f385129-2467-40b8-b481-16d324527c50.png)

<b>Retrieve employees in Finance or Sales</b>

Obtaining information on which employee machines to update for the Finance and Sales departments requires filtering for employee machines from only these two departments. To do this, I utilized SQL query creation and filtered for employee machines from employees in the Finance or Sales departments, as shown in the following code.

![image](https://user-images.githubusercontent.com/131769679/236782419-c786c8ea-e607-4d09-a818-74d51fb02a28.png)

<b>Retrieve all employees not in IT</b>

To perform a security update on employees who are not in the Information Technology department, it is necessary to identify which employee machines require updating. To accomplish this, I created a SQL query to filter for employee machines from employees not in the Information Technology department, as demonstrated by the following code.

![image](https://user-images.githubusercontent.com/131769679/236782659-7f04d74d-0907-424e-bbf2-bc7c031615e5.png)

<b>Summary</b>

By utilizing SQL queries with filters on the log_in_attempts and employees tables, I obtained specific information on login attempts and employee machines. I employed the AND, OR, and NOT operators to filter for the necessary data, and used the LIKE operator and the percentage sign (%) wildcard to search for patterns in the data.
