# ec2-with-rds-
```
created the VPC with public subnet and private subnet(2) nat gateway everything 
created the ec2 using the ubuntu machine
created the RDS using the DB subnet group giving the public access no
note : it asking the 2 subnets of AZ

```
```
After the installing the mysql workbench

mysql connection +
<img width="899" height="1599" alt="WhatsApp Image 2026-05-16 at 1 35 31 PM" src="https://github.com/user-attachments/assets/40426b5a-37b4-41a5-92d1-22fb790a5018" />

```

```
need to the user and password inside the mysql and that only need to access the only one database create that database also Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> 
mysql> 
mysql>

```
```
CREATE DATABASE projectdb;
```
```
CREATE USER 'projectuser'@'%' IDENTIFIED BY 'Project@123';

```
```
projectuser
Project@123
```

```
GRANT ALL PRIVILEGES ON projectdb.* TO 'projectuser'@'%';
```
```
FLUSH PRIVILEGES;
```
```
SHOW DATABASES;
```
```
SELECT user,host FROM mysql.user;

```
```
exit

```

```
mysql -h mydb.c1abcxyz.us-east-1.rds.amazonaws.com -u projectuser -p

```



