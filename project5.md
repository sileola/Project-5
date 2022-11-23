## PROJECT 5: CLIENT/SERVER ARCHITECTURE USING A MYSQL RELATIONAL DATABASE MANAGEMENT SYSTEM

First , I created and configured two Linux-based virtual servers (EC2 instances in AWS) and I named them as below:

Server A name - `mysql server`

Server B name - `mysql client`

Thereafter, I launched both instances


Next, on the mysql **SERVER** instance, I updated my packages, installed **mysql-server** and enabled the server by running the following commands:

`sudo apt update -y`

`sudo apt install mysql-server -y`

`sudo systemctl enable mysql`

Next, on the mysql **CLIENT** instance, I updated my packages, installed **mysql-client** and enabled the server by running the following commands:

`sudo apt update -y`

`sudo apt install mysql-client -y`

`sudo systemctl enable mysql`