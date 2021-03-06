2016 - CS684  PROJECT:AUTO SERVING BOT README TEMPLATE 
================================================ 
 
Group Info: 
------------ 
+   Amit Pathania(163054001)
+   Manjunath.K  (163050008)
+   Goutam (163050091) 
 
Extension Of 
------------ 
None
 
Project Description 
------------------- 
 
The Project aims to automate the process of serving orders in restaurant by using firebird V robot. We have successfully created an android application from which order can be placed by a customer and the order is served to his table by a firebird V robot.
The task was made more challenging by adding two more bots for serving and hence there was requirement of coordination among three bots to ensure proper delivery of orders and avoiding collisions and deadlocks. The same was achieved by using round robin scheduling algorithm for tasking bots and carefully designing onward and backward path from start point to destination and planning re-routing algorithms in real time to avoid collisions and deadlocks by using techniques similar to exponential backoff algorithm used for collision avoidance in computer networks using variable delays.  

 
Technologies Used 
------------------- 
 
+   Embedded C 
+   Xbee 
+   Python 
+   Android 
+   PHP/HTML/CSS
+   SQL
+   WAMP Server
+   CoralDRAW

    
 
 
Installation Instructions 
========================= 
 
Instal WAMP server. Refer video at https://www.youtube.com/watch?v=8b21rRN-hzo
Copy the php_server folder into "c:/wamp64/www" folder or folder location where WAMP server was installed
Use browser to open http://localhost/php_server/index.html 

To install Android Studio refer : https://www.youtube.com/watch?v=merqX4Qftls
 
To run FIREBIRD code: Open 2016-cs684-Auto Serving Bot\Code\Microcontroller Code\project folder. This folder contains .C and necessary.h files for installing firebird code.

Demonstration Video 
=========================  
The screencast of installing and running website. https://youtu.be/qan71FzF_-A

The screencast for using the Android project folder. https://youtu.be/VOe0TnxYKec

The screencast for Firebird code installation.   https://youtu.be/x7jXf04MPCw
