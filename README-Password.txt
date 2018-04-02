SQLplus , SQL oracle account:
vuduydu/vuduydu2018

//to create a new user:
create user <user_name> identified by <user_password>
grant connect,resource to <user_name>;

SELECT table_name FROM user_tables;

- To modify some constraints of a column using:
	SQL> alter table employee modify foreign key(dno) references Department(dnumber);

SQL> select Department.* from Department, Dept_locations where department.Dnumber = Dept_locations.Dnumber order by Dept_locations.Dlocation;

   DNUMBER DNAME           MGR_SSN   MGR_START
---------- --------------- --------- ---------
         5 Research        333445555 22-MAY-88
         5 Research        333445555 22-MAY-88
         1 Headquarters    888665555 19-JUN-81
         4 Administration  987654321 01-JAN-95
         5 Research        333445555 22-MAY-88

On 16/04/2018, there will be viva.