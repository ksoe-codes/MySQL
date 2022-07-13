create database employee;
use employee;

create table employee(
	Number int, 
    Name varchar(20), 
    Salary int, 
    Department varchar(20), 
    Manager varchar(20), 
    Experience int, 
    Rating varchar(20), 
    Skillset varchar(20)
    );
drop table employee;
select * from employee;
    
insert into employee values( 01 , "Kiara" , 20000 , "Development" , "Sujata" , 1 , "Met Expectation" , "C" );
insert into employee values( 02 , "Katrina" , 57500 , "Accounts" , "Archit" , 6 , "Commendable" , "Java" );
insert into employee values( 03 , "Selina" , 15500 , "HR" , "Sushant" , 11 , "Needs Improvement" , "C++" );
insert into employee values( 04 , "Herleen" , 56000 , "Development" , "Sushant" , 2 , "Outstanding" , "Python" );
insert into employee values( 05 , "Shruti" , 42000 , "Sales" , "Archit" , 11 , "Met Expectation" , "C++" );
insert into employee values( 06 , "Deepika" , 280000 , "Accounts" , "Sujata" , 30 , "Outstanding" , "C" );
insert into employee values( 07 , "Parineeti" , 10000 ,  "HR" , "Sushant" , 1 , "Needs Improvement" , "C++" );
insert into employee values( 08 , "Nina" , 50000 , "Development" , "Sujata" , 15 , "Met Expectation" , "Python" );
insert into employee values( 09 , "Avneet", 72000 , "HR" , "Archit" , 4 , "Outstanding" , "Java" );
insert into employee values( 10 , "Billie" , 15500 , "Sales" , "Sushant" , 11 , "Needs Improvement" , "C" );
insert into employee values( 11 , "Tara" , 10000 , "Sales" , "Sushant" , 1 , "Needs Improvement" , "Java" );
insert into employee values( 12 , "Hailey" , 64000 , "Development" , "Sujata" , 3 , "Outstanding" , "C++" );
insert into employee values( 13 , "Anushka" , 111000 , "HR" , "Archit" , 18 , "Commendable" , "Java" );
insert into employee values( 14 , "Ashley" , 32000 , "Development" , "Sujata" , 6 , "Met Expectation" , "Java" );
insert into employee values( 15 , "Kendall" , 104000 , "Sales" , "Archit" , 8 , "Outstanding" , "C++" );
insert into employee values( 16 , "Sara" , 13500 , "Development" , "Sushant" , 7 , "Needs Improvement" , "C" );
insert into employee values( 17 , "Rakul" , 84000 , "Accounts" , "Sushant" , 12 , "Commendable" , "C++" );
insert into employee values( 18 , "Shraddha" , 93000 , "Development" , "Sushant" , 14 , "Commendable" , "Java" );
insert into employee values( 19 , "Camila" , 10000 , "Accounts" , "Sushant" , 1 , "Needs Improvement" , "C++" );
insert into employee values( 20 , "Nora" , 72000 , "Sales" , "Archit" , 4 , "Outstanding" , "C++" );

select * from employee;

/*
Query 1:
	Highest Salary
    
Query 2:
	Lowest Salary

Query 3:
	Count of Employees Per Department:

Query 4:
	Ascending order based on
    1. Experience
    2. Salary

Query 5:
	Retreive 
    1. > 10 years of experience and Commendable.
    2. < 5 years of experience and Outstanding.

*/

/* Query 1 */
select * from employee where salary = (select max(salary) from employee);

/* Query 2 */
select * from employee where salary = (select min(salary) from employee);

/* Query 3 */
select Department , COUNT(*) from employee group by Department;

/* Query 4 */
select * from employee order by Experience asc;
select * from employee order by Experience desc;

select * from employee order by Salary asc;
select * from employee order by Salary desc;

/* Query 5 */
select * from employee where (experience > 10) and (rating = "Commendable");
select * from employee where (experience > 5) and (rating = "Outstanding"); 
