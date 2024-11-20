 # EX 6: CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 # NAME:RAMYA P
 # REG NO:212223230168
 # DATE:20-11-24
## AIM
  
  To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.




## ALGORITHM

 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.


 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache


 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.


 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.


 
## COMMANDS
# webserver
To install httpd:
     yum install httpd -y
  
To enable and start httpd :
~~~

   systemctl enable httpd
   systemctl start httpd
~~~
Create a simple HTML page :

cd /var/www/html

test.php

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
~~~



## OUTPUT
# TERMINAL
![image](https://github.com/user-attachments/assets/f55f152c-21a7-4392-b823-0e3df185f165)
![image](https://github.com/user-attachments/assets/f8e25217-3cce-4bff-9079-c75baa3fa254)

![image](https://github.com/user-attachments/assets/4c5916c1-ec66-4492-90bd-375728fefe51)
# WEBPAGE
![image](https://github.com/user-attachments/assets/38009dfd-02ad-49ed-af6c-1527aeb212e3)






 

## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  


