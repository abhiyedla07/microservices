# microservices
I have Completed My 2nd task of Infotrixs Internship
>> Task: Deploy a wordpress Site in aws under Microservice Architecture.
How did i complete task?
>After Understanding the problem well, I decided what resources will be needed.
>Created 2 EC2 (Ubuntu server)(1 for webserver & 1 for sql-server) set vpc and security group.
>Login in 1st server and updated server with apt update command.
>Installed apache2 server and php dependencies.
>Download wordpress and unzip the folder and copied all files under /var/www/html/
>Login in 2nd server and installed my sql server
>Created new user, database and gave all privileges.
>Copied ip of 1st server (web server) and opened in web browser
>Configured wordpress > in database host gave ip of sql server >login in wordpress and created home page
