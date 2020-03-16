# Social Network Website
# Forked from https://github.com/iPynch/Simple-PHP-Social-Network-Website. Thanks iPynch.
# Made vulnerable on purpose. 
This is a simple social network website designed with core php and of course with the aid of the html, css and core javascript.
It supports the following functionalities:
* User registeration
* Creation of post with possibility of stamping a picture along with it
* Sending and recieving friend requests as well as accepting or ignoring them
* Viewing profiles and your relation with them
* Channging profile picture
* Simple search

<br>

## Notes:
* Home shows all public posts. It doesn't show private posts except if the poster is on your friend list.
* Posts are displayed in chronological order from latest to oldest.
* Home also shows your own posts.
* Initially created accounts have a default profile picture based on their gender.
* Different users may suffer layout inconsistency or rather not the required smooth interface if the specified font isn't installed on the user's device (to be solved).

<br>

## Few Screenshots to demonstrate website layout and interface:

![alt text](https://imgur.com/QZeud9E.png)
![alt text](https://imgur.com/fy5FLIX.png)
![alt text](https://imgur.com/E6xmAgL.png)
![alt text](https://imgur.com/PaxbrHJ.png)

<br>

## To install this application:
* Create a database from DDM.sql file which is found within database folder.
* Import simple data test from DML.sql to create a simple instance of data (passwords of users are equivalent to the first names).
* You need a webserver (either local or global) to launch .php files. Programs like Xampp, WampServer provides a local webserver that uses MySQL database.
* copy all other files to your a new folder (folder name is of your choice that is the website name) inside htdocs folder within your program and run.
