# OKS-Manegement-System
Database Project


 
                              KHULNA UNIVERSITY OF ENGINEERING & TECHNOLOGY
                              Department of Computer Science and Engineering (CSE)
                              PROJECT ON CSE3110
                              Course Title: Database Systems 

Project Name:  Organization of KUET Sports Database Management System
Submitted To:				
1. Md. Masum Al Mesba				
Assistant Professor			
Department of Computer Science and Engineering (CSE)	
Khulna University of Engineering & Technology (KUET)	
2. Nazia Jahan Khan Chowdhury		
Assistant Professor			
Department of Computer Science and Engineering (CSE)	
Khulna University of Engineering & Technology (KUET)	

Submitted by:
MD. Parvej Mia
Roll: 1807081
Year: 3rd Semester: 1st
Submission Date: July 21, 2022

Project Overview
All the information of a Sports club needed can be managed in this project. Information about the current students, alumni, current players, club fund, club events all of these can be managed in this project. Here we can able to see the information about the players, which sports he/she likes to play or we can know about the event details organized by OKS.


Database Structure
The database consists of six tables and they are students, current_students, alumni, funds, players, events.
Students table has one to one relationship with alumni and current_students table. Current_students table has one to many relationship with event and players table. Alumni table has one to many relationship with funds.











ER Diagram:

 
![image](https://user-images.githubusercontent.com/61575111/183556385-f6205f82-1279-42a7-a372-26dd1ced8ecc.png)



Schema Diagram: 

![image](https://user-images.githubusercontent.com/61575111/183557642-5839301a-e4dc-46fe-b1fb-ff949c77c289.png)



Functionality
Some main functionality of this database project are given bellow.
1.	Here one PL/SQL block that shows the information of events information with the respective players who participated on those events.
![image](https://user-images.githubusercontent.com/61575111/183556494-034ae4b5-9120-49b0-a31c-2bf351eec6bc.png)

 
2.	By this procedure a user can input fund data on funds table:
 ![image](https://user-images.githubusercontent.com/61575111/183556506-3bf8c606-aff3-4b31-8efa-619f92ca432a.png)


3.	Here is one Trigger it will automatically set the batch of a student when we insert or update data on students table.
 ![image](https://user-images.githubusercontent.com/61575111/183556524-e638c88d-43c5-4baf-8986-115b30f2fd20.png)

 
4.	Here a PL/SQL block that will show the final balance of an account from funds table after calculating the interest.
 ![image](https://user-images.githubusercontent.com/61575111/183556539-5b8c8d1c-d74f-4b6f-b516-9615faf20148.png)


Database Design Process
This database project is developed by ORACLE. I developed six new tables and inserted data from file. 
I learned several important lessons through the design process. These include:

1)	Designing tables is the most important step and must be done early in the project.

2) Building a database from scratch is often easier than revising an existing database– which is why initial design is so important and was stressed throughout the course!


Discussion & Conclusion
The project was a learning experience for us and allowed us to improve upon our SQL skills. From this we learn about database management system, SQL query, function procedure, trigger, cursor etc. that help us for future database development. We developed a database system for managing the information of Organization of KUET Sports. 

Reference
https://www.w3schools.com/sql/






