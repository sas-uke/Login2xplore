# *Login2Xplore---JsonDB-Project*
A small project to demonstrate the new technology - JsonDB.

### :warning: *Warning !* ## 
*Since the api uses Http-connection (and not Https) and all the webhosting servers only allow Https connections.
So, This site faces the issue of sending and retrieving data. This issue will be resolved as soon the developers provide a secure-connection to API.
Although the illustrations are provided on the complete process.
But still if anyone wants to check this beautifully constructed page, Welcome !*

__Hosted Site link__  :  https://login2xplore-project.herokuapp.com/index.html    

## *Introduction*
    -This is a simple and elegant HTML,CSS,Js/jQuery Login/SignUp Page,
              to demonstrate the data sending & request handling over JsonPoweredDB-api for database management.
    -This project uses JsonPoweredDB for the backend usage of saving all users data in the Json-format.
    -Being the most efficient database, the time taken to POST & GET user-data from the database is almost null.
    -Unlike SQL and relational databases, this JsonPoweredDB feels user and developer friendly.
    
## *Easiest Syntax Usage :*
    
    // GET - Query
    
    {
    "token": "2134770734|19056227XXXXX281054|2134XXXXXX",
    "cmd": "GET",
    "dbName": "Company",
    "rel": "Employee",
    "jsonStr":{
        "empName": "Oshin Pojta"
        }
    }
    
    // INSERT - Query
    
    {
      "token" : "90935402|-31948797XXXX293566|909XXXX",
      "cmd" : "PUT",
      "dbName" : "Emloyee",
      "rel" : "Emp-rel",
      "jsonStr" : {
        "name" : "Oshin Pojta",
        "email" : "Sujanian785@gmail.com",
        "mobile" : 7018516XXX,
        "address" : "Solan"
            }
    }
    
*If there is no Database named - 'Employee', It will automatically create Database with the name without forcing developers to write code or throwing hundreds of errors.*

## *Benefits of using JsonPowerDB*
    -Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
    -Serverless support for faster development - A UI developer can develop complete dynamic application.
    -DBMS with built in web / application server and embedded caching makes the performance lightning fast.
    -Server side Native NoSQL - best query performance.
    -In-built support to query on multiple JPDB databases.
    -Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
    -Schema free - easy to develop and maintain.
    -Web-services API - Can be used with any programming language that has support for HTTP.
    
## *Illustrations*

![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/1.Sign-Up.png "SignUp")
*-- Tapped to SignUp Page*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/2.Sign-Up.png)
*-- Values Entered*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/3.Sign-Up.png)
*-- Registered to DB*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/4.Sign-In.png)
*-- Tapped to Login Page*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/5.Sign-In.png)
*-- Entered Credentials*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/6.Sign-In.png)
*-- Server Response with user-data stored in*


![image](https://github.com/oshinpojta/Login2Xplore---JsonDB-Project/blob/main/Screenshots/7.Inserted.png)
*-- Inside the database-Admin-panel*


## Release History
*Originally developed by Oshin Pojta, the then under-graduate from Lovely Professional University,
                          for the demonstration of JsonPoweredDB on Feb-14,2021. 
    -This project is a testimony of the course provided by Login2Xplore Company, 
     that demonstrates the usage and functionality of Json-Powered Database. 
    -The date of submission of this project was by Feb-15,2021.* 

## Sources

*CodePen.io , Youtube.com, SweetAlert.js.org, BootStrap and jQuery for Frontend.*

*Login2Xplore Documentation link for Backend & Miscellaneous Query-Reference* : http://login2explore.com/jpdb/index.html#introduction-jpdb
