
****To create a MySQL DB instance with WORKBENCH steps****

 1)Sign in to the AWS Management Console and open the Amazon RDS console.

 2)In the navigation panal, choose Databases.

 3)Choose Create database and make sure that standard Create is chosen.
 
 4)In Configuration, choose MySQL.

 5)For DB instance size, choose Free tier.

 6)For DB instance identifier, enter a name for the DB instance, or leave the default name.

 7)For Master username, enter a name for the master user, or leave the default name.
 
 8)To enter your master password, disable Auto generate a password, and then enter the same password in Master password and Confirm password.
 
 9)To use an automatically generated master password for the DB instance, enable Auto generate a password.

 10)In connectivity choose "additional connectivity configuration" -> in that choose public accessible to "YES" and enter database port no to 3306

 11)Choose Create database. 


 
 ****To connect to a database on a DB instance using MySQL monitor****
 1)now press on database name to connect with mysql workbench
 2)Find the endpoint (DNS name) and port number for your DB instance.On the Connectivity & security tab, copy the endpoint.
  Also, note the port number. You need both the endpoint and the port number to connect to the DB instance.
 3)now open workbench and create new database with this port number and then check connection after that it require password 
 so put it into bracket and press ok button.
 4)now after entering into workbench create database and table regarding to it.
