# Project 5

updating & upgrading ubuntu on client and server side

` $ sudo apt update`

` $ sudo apt upgrade`

![](images/supdate1.png)

![](images/supgrade3.png)

![](images/cupdate2.png)

![](images/cupgrade4.png)

installing mysql server and mysql client respectively

` $ sudo apt install mysql-server`

` $ sudo systemctl enable mysql`

` $ sudo systemctl status mysql`

![](images/sinstserver5.png)

![](images/senastatus6.png)

` $ sudo apt install mysql-client`

![](images/cinstall7.png)

editing server's aws inbound rule to only allow client's ip

calling client's ip from terminal to include in inbound rule

` $ ip addr show`

![](images/sinbound8.png)

![](images/ipaddr8.png)

securing sql server and removing unwanted additions

` $ sudo mysql_secure_installation`

![](images/ssecurinstall9.png)

entering mysql server and populating it 

` $ sudo mysql`

![](images/ssql11.png)

editing mysql bind-address configuration to allow access from any ip address

![](images/sconf12.png)

![](images/sconff12.png)

connecting to mysql server from client without ssh and confirming access to the database

` $ sudo mysql -u remote_user -h ipaddress -p`

![](images/finalcntn13.png)