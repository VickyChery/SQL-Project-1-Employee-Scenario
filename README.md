# SQL-Project-1-Employee-Scenario

Table 1 Query:
Create Table EmployeeDemographics 
(EmployeeID int, 
FirstName varchar(50), 
LastName varchar(50), 
Age int, 
Gender varchar(50)
)

Table 2 Query:
Create Table EmployeeSalary 
(EmployeeID int, 
JobTitle varchar(50), 
Salary int
)

Table 1 Insert:
INSERT INTO EmployeeDemographics VALUES
(1001, 'Jim', 'Carey', 30, 'Male'),
(1002, 'Ashley', 'James', 25, 'Female'),
(1003, 'Adrian', 'Sinclair', 26, 'Male'),
(1004, 'Sean', 'John', 21, 'Male'),
(1005, 'Samantha', 'Williams', 30, 'Female'),
(1006, 'Jeff', 'Alexander', 30, 'Male'),
(1007, 'Bobby', 'Doe', 25, 'Male'),
(1008, 'Anthony', 'Jones', 25, 'Male'),
(1009, 'Antonia', 'Jackson', 26, 'Female'),
(1010, 'Lisa', 'Joseph', 22, 'Female');

Table 2 Insert:
INSERT INTO EmployeeSalary VALUES
(1001, 'Senior Data Engineer', 125000),
(1002, 'Data Analyst', 95000),
(1003, 'Junior Data Analyst', 65000),
(1004, 'Data Engineer', 85000),
(1005, 'Senior Data Engineer', 135000),
(1006, 'Business Analyst', 85000),
(1007, 'Business Analyst', 85000),
(1008, 'Senior Business Analyst', 115000),
(1009, 'Senior Business Analyst', 115000),
(1010, 'VP Analytics', 185000);
