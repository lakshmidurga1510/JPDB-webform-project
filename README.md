# JPDB-webform-project
## Webform project
### Description
___
JPDB-webform-project is a simple project on developing a web form using HTML5/JavaScript, the details entered in that from can be stored in the JPDB-JsonPowder DB.
This project is all about learning the basics of JPDB.
Some of the basics include validating a form, Storing data and performing CRUD operations on the Database using Talend API Tester.
___
## Benefits of using JsonPowerDB
+ Schema-free - Easy to maintain.
+ Low development cost.
+ In-built support for quering multiple Databases.
+ Any software application that needs back-end Database can use JsonPowerDB.
___
## JasonPowerDB Sample code includes the following:
Using PUT 
-This command is used to create a database and relation and to store the data in the created database on JPDB.

    {
    "token": "90938687|-31949284814585865|90946146",
    "cmd": "PUT",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr": {
        "name": "Lakshmi",
        "email": "lakshmi059@gmail.com",
      "mobile_no":8106566604
    }
  } 

Using UPDATE
-This command is used to update the data in the specified database on JPDB.

    {
    "token": "90938687|-31949284814585865|90946146",
    "cmd": "UPDATE",
    "dbName": "Student",
    "rel": "Student_rel",
    "jsonStr": {
      "1":{
        "Section":"A"
    }
   } 
   
  Using UPDATE
-This command is used to delete the row of data in the specified database on JPDB.

    {
    "token": "90938687|-31949284814585865|90946146",
      "cmd": "REMOVE",
    "dbName": "Student",
    "rel": "Student_rel",
     "record":1
    }
   } 
 
 ## Illustrating the Project

![2022-04-19 (2)](https://user-images.githubusercontent.com/103915474/163980163-192253ea-a93b-4253-816e-96a7662d62e8.png)

![2022-04-19 (3)](https://user-images.githubusercontent.com/103915474/163979964-72ef8916-5956-4c0f-9dd3-5da4822a06a8.png)

![2022-04-19 (4)](https://user-images.githubusercontent.com/103915474/163980091-cda38094-b1b5-4144-a7aa-b7ebcd5ca7fe.png)

![2022-04-19](https://user-images.githubusercontent.com/103915474/163980143-795041dd-32fe-47a4-8f23-7bc47f8295f5.png)

![2022-04-19 (1)](https://user-images.githubusercontent.com/103915474/163980213-214eaccb-1812-41b3-89d2-c5f028b051cb.png)



