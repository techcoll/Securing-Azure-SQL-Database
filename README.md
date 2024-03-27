# Securing-Azure-SQL-Database

## Objective
1. create a basic application environment consisting of a virtual network, Linux VM, and SQL Database

2. limit network access to your Azure SQL Database by utilizing server-level firewall IP rules and virtual network access

3. create database users and roles to easily manage permissions in your database

4. enable Auditing and Temporal Tables to monitor executed queries and changes to your data

5. configure a backup policy for your Azure SQL Database

### Skills Learned
By the end of this project, you will be able to secure your Azure SQL Database.

### Tools Used
Microsoft Azure free account
SQL Server Management Studio

## Steps 1
*Ref 1A: Create a resource group and a virtual network with a subnet range 0f 10.2.0.0/24*
![1a](https://github.com/techcoll/Securing-Azure-SQL-Database/assets/107801057/c2df35bc-7a03-429f-ad7e-90fdb141c0bc)

*Ref 1B: Create a virtual machine*
![1b](https://github.com/techcoll/Securing-Azure-SQL-Database/assets/107801057/a75ac448-1089-436f-a25d-29d107215a34)

*Ref 1C: Create an SQL database*
![1C](https://github.com/techcoll/Securing-Azure-SQL-Database/assets/107801057/7d8a7f14-89fd-412c-bf59-e6adc56f804a)

## Steps 2
*Ref : Refused login from a public IP address because IP  has not been added to the rule*
![2a](https://github.com/techcoll/Securing-Azure-SQL-Database/assets/107801057/4998f4d9-d32a-4cee-af7c-4f12c1f9b878)




