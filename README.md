AWS DATABASE MIGRATION 

In this workshop, I explored how you to migrate your data to and from databases using the AWS Database Migration Service (DMS) and AWS Schema Conversion Tool (AWS SCT).


Steps taken to complete the activity:
1) Creation of EC2 KEY PAIR. Download this to your machine.
2) Cloudformation template I used the template provided in the AWS workshop: 
3) Configuration of Environment
![B2C9A309-A167-4777-A76F-5743C3670A32](https://user-images.githubusercontent.com/95499741/144904690-e1aa481e-6ede-4f64-95a3-98adaa835816.png)
4) Selection of module: MICROSOFT SQL SERVER TO AMAZON RDS FOR SQL SERVER ( As a prerequisite of this step, we used Remote Desktop Protocol (RDP) to connect to the Amazon EC2 Instance. Please ensure you have a RDP client such as Microsoft Remote Desktop installed on your workstation)

5) The environment for this lab consists of:
A Microsoft SQL Server running on an EC2 instance as the source database. This server is also used run Microsoft SQL Server Management Studio.
A Microsoft SQL Server instance running on AWS RDS as the target database.

6) CONNECT TO THE EC2 INSTANCE 
7) CONFIGURE THE SOURCE DATABASE
8) CONFIGURE THE TARGET DATABASE
9) CREATE A DMS REPLICATION INSTANCE
10) CREATE DMS SOURCE AND TARGET ENDPOINTS
11) CREATE A DMS MIGRATION TASK
12) INSPECT THE CONTENT OF TARGET DATABASE
13) REPLICATE DATA CHANGES
