# Team Members:

- Mohamad Kassem
- Arjun Puliyasseri

#To Run The Project:

1- Using AWS, manually create: EC2 instance, S3 bucket, 2 Fifo queues.

2- Connect to your EC2 instance using SSH.

3- Run the Worker code as Maven Build to generate a Jar file.

4- Upload the Jar file to your EC2 instance using SFTP (Use suitable method accoring to your OS).

5- Now it is time to run our worker jar file on EC2 instance, to do that we have several methods. You are free to use any of them. One of these is to use the direct terminal that comes with EC2 instance on the AWS website. You can access it though: YourEC2Instance -> Connect -> "Ec2 Instance Connect" Tab -> Connect.

6- Run Client.java Locally.
