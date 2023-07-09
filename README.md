# WMS
Software Engineering Course Project

1.Product Perspective 
Project managers often spend a lot of time planning how work will be executed. Work Management System
helps eliminate the back-and-forth and navigational confusion that can accompany using numerous 
spreadsheets and digital file-storage platforms to track work. Instead of siloing tasks into different spaces, 
Work Management Software houses all tasks and resources within one platform. 
The Work Management System (WMS) is a software application aimed at simplifying and organising
various tasks like adding/editing/deleting worker details, adding new worker details, performing worker
assignment to works, marking work status as complete, and displaying work and worker details.
Thus, WMS provides a user-friendly, efficient, and secure platform to large amount of data and process
requests, helping organisations control and optimize the productivity of their teams.

Dependencies:
− Python3
− MySQL Workbench: Database
− Python tkinter Graphical User Interface(GUI): Frontend

2 databases would be maintained: 
• Work database: This database stores all the works currently in the system and their details, which are :-
 - Status
 - Priority
 - Requirements
 - Start date
 - Duration 
•
•
Workers’ database: This database stores all the workers involved and their basic details, which are :-
 - Name
 - Skill level
 - Roles
 - Work assigned
 - Availability
 - Work done
 - Number of hours worked

System Features 
 
• User/Admin: 
Access to central database: 
The Admin, being the superuser, has the ability to:
- Add/modify/delete the worker details
- Add the work details
- Assign workers to the works
- Mark work status as completed
- Display worker and work details

System specifications:
Skill Level: The user can specify the expertise of a worker as beginner, intermediate or expert. 
Work requirements: The user can specify the requirements of a work in the terms of the number of 
 workers of a specific role and skill level required.
Work duration: The duration of a work is defined as the number of days from its start date till the date
 it is marked as completed by the user, excluding the weekends.
Availability: The availability of a worker is defined in boolean as 0 (unavailable) or 1 (available).
Start date: The start date of a work is the date when the requirements of the work are fulfilled and when it 
 can be started according to the priority list.
