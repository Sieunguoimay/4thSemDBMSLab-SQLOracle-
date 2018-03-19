SQLplus , SQL oracle account:
vuduydu/vuduydu2018

//to create a new user:
create user <user_name> identified by <user_password>
grant connect,resource to <user_name>;

SELECT table_name FROM user_tables;


- To modify some constraints of a column using:
	SQL> alter table employee modify foreign key(dno) references Department(dnumber);

- Question 14:
	https://drive.google.com/file/d/1buo3LT8EeNTXvnrofGmNaU_uE6OxMcAh/view