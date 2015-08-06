## Steps for Install OwnCloud 7 on CentOS 7
1 Create a new Virtual machine
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/1.JPG)

2 Configuration 
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/2.JPG)

3 Guest Operating System installation
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/3.JPG)

4 select a guest operating system
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/4.JPG)

5 name the virtual machine
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/5.JPG)

6 specify disk capasity
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/6.JPG)

7
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/7.JPG)

8 installing CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/8.JPG)

9 installing CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/9.JPG)

10 installing CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/10.JPG)

11 installing CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/11.JPG)

12 create user
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/12.JPG)

13 configuration
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/13.JPG)

14 configuration
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/14.JPG)

15 login to CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/15.JPG)

16 start using  CentOS
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/16.JPG)


20 Install CentOS 7 with default Minimal configuration then install all current updates:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5pics/20.JPG)

21 install PHP, Apache web server and MySQL server and some php extensions:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/21.JPG)

22
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/22.JPG)

23
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/23.JPG)

24
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/24.JPG)

25
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/25.JPG)

26 Set SELinux to allow OwnCloud to write the data:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/26.JPG)

27 Allow web traffic through the firewall:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/27.JPG)

28 Start Apache using the following command:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/28.JPG)

29 Start  MariaDB by issuing this command:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/29.JPG)

30 Auto start the service at system start-up:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/30.JPG)

31 download ownCloud from official website. 
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/31.JPG)

32 Extract the archive we just downloaded.
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/32.JPG)

33 assign the permission for web server to read and write the files on cloud directory.
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/33.JPG)

34 Configure the mariadb instance.
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/34.JPG)

35 
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/35.JPG)

36 ###Create the ownCloud database and user.
   ##Login to mysql server, Using the following command
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/36.JPG)

37 Apache server configuration
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/37.JPG)

38 Set the following lines in the config file.
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/38.JPG)

39 Restart all apache and mariaDB services:
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/39.JPG)

40 Open web browser and paste http://<my_ip_address>/owncloud
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/40.JPG)

41 Now we can own cloud storage
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/41.JPG)

42 Now we can own cloud storage
![alt text](https://raw.githubusercontent.com/sankag/ESBII/master/lab5Pics2/42.JPG)
