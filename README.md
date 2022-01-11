# Normalization-of-Database-using-Armstrong's Axioms and Oracle Sql

The Payroll department of a  Research And Development firm, maintains a spreadsheet that contains each employee's pay information. The schema of this table is PAYROLLS(emp_id, name, position, rate, phone, dept, mgr_ID, mgr_name, room, bCode, bName, hrs, payDate, pay)

## The table’s 14 attributes are:
emp_id - a number that uniquely identifies an employee
name - an employee's full name
position - an employees job title
rate - the hourly wage that the employee is paid
phone - an employee's work phone
dept - the name of the department in which the employee works. Department names are unique.
mgr_ID - the emp_ID of the employee who manages the dept department.
mgr_name - the name of the manager of the employee's department
room - the room number of the department
bCode - A 3-character building code in which the department's room is located. bCode uniquely identifies a building.
bName - the name of the building that the room is located in
hours - the hours worked by the employee during the pay period
payDate - the date on which the employee is being paid
pay - the amount the employee is being paid on this payDate


## Some business rules:
Employees are paid every 2 weeks. 
emp_id and paydate uniquely identify each row of the above PAYROLLS table.
Each employee belongs to one department.
An employee's rate of pay is determined by their position.
Each department is managed by one employee. An employee can manage many departments.
Each department has a location that is specified by a room number (room) and building (bCode).
A standard workweek is considered to be 40 hours per week. Any work performed in a two-week period that exceeds 80 hours is considered overtime.
Overtime work is paid at a rate of 1.5 times each employee's rate value.
Pay is a calculated value and should not be stored as a column in the database that you create.


