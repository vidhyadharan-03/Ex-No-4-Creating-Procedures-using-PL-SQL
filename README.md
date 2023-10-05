# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
SQL> CREATE TABLE empl(
  2       empid NUMBER,
  3       empname VARCHAR(10),
  4       dept VARCHAR(10),
  5       salary NUMBER
  6      );

SQL> CREATE OR REPLACE PROCEDURE insert_emp1_data AS
  2      BEGIN
  3      insert into emp1(empid,empname,dept,salary)values(1,'Vidhyadharan','CEO',12000000000);
  4      insert into emp1(empid,empname,dept,salary)values(2,'Dineshkumar','CTO',120000000);
  5      insert into emp1(empid,empname,dept,salary)values(3,'Surender','CFO',120000);
  6      commit;
  7      end;
  8      /
 10     begin
  2     insert_emp1_data;
  3      end;
  4     /
 ```
### Output:

![exp4-1](https://github.com/vidhyadharan-03/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/114286357/304490c7-b9f3-4542-918c-2250d810d6e3)
![exp4-2](https://github.com/vidhyadharan-03/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/114286357/3e7ea653-f4ca-4cdd-9b43-2d153f65f5a6)

## out:
![exp4-out](https://github.com/vidhyadharan-03/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/114286357/3817e40d-b8bf-4d22-b179-df3c0ee1133d)

### Result:
THE PROGRAM HAS BEEN IMPLEMENTED SUCCESSFULLY
