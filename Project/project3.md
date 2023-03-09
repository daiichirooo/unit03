![](cooking.png)

# Unit 3 Project: "LISTMATE" cooking ingredients record app

# Criteria A: Planning

## Problem definition
Kai Eduardo Suzuki is a G11 student at UWC ISAK Japan. He cooks a lot, but finds it difficult to keep track of all the ingredients he has. This is because he loses track of where each ingredient is kept in his fridge and in his room. Also, he cannot keep track of the expiry dates of all the ingredients, so sometimes he finds himself not being able to eat them anymore. Therefore, I would like to create an application on my computer that allows me to keep track of where each ingredient is stored and when its expiry date is. The application also needs a login system, as several people may use this application and we want to keep track of progress accordingly.

## Proposed Solution
Considering the client's requirements, a suitable solution would include a localised computer programme with a graphical user interface (GUI) that can store data in a database. The database is SQLite, an embedded serverless relational database, so both the programme and the database can be localised.ORM is a database abstraction layer that intervenes between the code and the database engine simplifies queries and makes the code more concise; for the GUI, we use KivyMD, which is elegant and simple. This GUI framework is structured in an object-oriented format to facilitate development.



### Design Statement ### 
I will design a Python application that runs on the KivyMD GUI framework and stores data in an SQLite database for Kai Eduardo Suzuki. The application allows him to put food that he bought into the database as input, allows him to see the list of the food and its expiration date, and allows him to edit the amount or delete the food. The application is protected by a hashed login system, which allows users to manage their progress individually and privately. It takes approximately one month to complete and is assessed against the following criteria.


## Success Criteria ##

1. The application allow the users to add new food items with its information such as the amount of food, the place user stored it, and the expiration date of the food.
2. The application has the list on the home screen which shows the food substances with an expiry date of less than 5 days.
3. The application show the foods by locations (fridge1, fridge2, room).
4. The application has the ability that users can make a change in the amount of food on the list when they use some of the food ingredients.
5. The application has a secure login and registration system.
6. The application allow the user to delete the food items if they have added to the list by mistake.


# Criteria B: Design
## System Diagram
![Fig.1 System diagram of the LISTMATE](system_diagram.png)
Fig.1 System diagram of the LISTMATE

## Data Storage
![Fig.2 diagram the shows the structure of database of LISTMATE](data_storage.png)
Fig.2 diagram the shows the structure of database of LISTMATE

## UML Diagram
![Fig.2 UML diagram of LISTMATE. This diagram depicts the classes of the application.](uml_diagram.png)
Fig.3 UML diagram of LISTMATE. This diagram depicts the classes of the application.

## Wireframe
![](wireflame1.png)
Fig.4 Wireframe of the LISTMATE.

## Record of Tsaks

| Task No | Planned Action                                           | Planned Outcome                                                                                                                    | Time estimate | Target completion date | Criterion |
|---------|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Have a meeting with client          | understand the requirements and be prepared for starting the project                                                                                        | 10 min         | Feb 7                  | A         |
| 2       | Write the problem definition and proposal solution          | understand the situation of client and organize my tasks                                                                           | 30 min          | Feb 8                 | A         |
| 3       | Write the success criteria                               | To define what I have to do for my client                                                                           | 5 min          | Feb 14                | A         |
| 4       | Meet the client and show him the success criteria                    | Ask him to give me a signiture on the success criteria paper                                                                                                           | 10 min         | Feb 16                 | A         |
| 5       | Creating Wireframe                                       | To have Wireframe diagram finished and get a visual image of the service                                                                                             |   30min       |     Feb 21          |   B    |
| 6       | Start working on the python and kyvyMD                     | To have the basic foundation of the code                                                                                          | 1hr         | Feb 23                  | C         |
| 7       | Code the login function                    | To have a login system with the userid and hashed password.                                                                                       | 1hrmin         | Feb 23                 | C         |
| 8       | Code the signup function                                                           | To have a signup system.                                           | 1hrmin         | Feb 23                 | C         |
| 9       | Create the main database of the project                                | To have the main database which is going to be a foundation of the service                                                                             | 15 min        | Feb 23                  | C         |
| 10       | Code the home screen                    | To have a asethetic homepage of the service.                                                                                       | 30rmin         | Feb 25                 | C         |
| 11       | Code the add function                    | To have a add screen which is easy to use.                                                                                       | 1 hr         | Feb 25                 | C         |
| 12       | Code the list function                    | To have a list screen which is easy to use.                                                                                       | 1 hr         | Feb 25                 | C         |
| 13      | Add the table on List screen                   | make user be able to use and see the table from the screen.                                                  | 1 hr        | Feb 28                | C         |
| 14      | Code the delete function                               | To make the function to remove food from the database                                                                   | 1hr         | Feb 28                  | C         |
| 15      | Code the 5 days expiration date notification table on HomeScreen       | Make user be able to reseive the notification                                                       | 30 min        | Feb 28                  | C         |
| 16      | Code the update function               | To make the function to update the food to the database                                                              | 30 min        | Mar 2                  | C         |
| 17      | Code the calender system on the AddScreen | make users be able to add the expiration date easier.                                   | 1 hr        | Mar 4                  | C         |
| 18      | Code the button(place) on the AddScreen | make users be able to add the place they stored date easier.                                   | 1 hr        | Mar 4                  | C 
| 19      | Code the change button                       | make users be able to change the amount of the food when they eat.                                                                                      | 1hr         | Mar 5                  | C         |
| 20      | Code the validation for Login system                          | To notice the users if there are some mistakes on userid or password                                                      | 1hr        | Mar 5                  | C         |
| 21      | Code the validation for Signup system                          | To notice the users if there are already same userid on the database and email                                                      | 1hr        | Mar 5                  | C         |
| 22      | Coding the pop up dialogs                                | To have pop up dialogs implemented to improve user experience                                                                      | 30 min        | Mar 3                  | C         |
| 23      | Coding Input Validation                                  | To have input validation implemented throughout the application to ensure data inputted is correct                                 | 20 min        | Mar 3                  | C         |
| 23      | Creating System Diagram                                  | To have system diagram finished                                                                                                    | 30 min        | Mar 3                  | B         |
| 24      | Creating UML Diagram                                     | To have the UML diagram finished                                                                                                   | 30 min        | Mar 3                  | B         |
| 25      | Creating ER Diagram                                      | To have the ER diagram finished                                                                                                    | 30 min        | Mar 3                  | B         |
| 26      | Creating Flow Diagrams                                   | To have the  flow diagrams finished                                                                                                | 30 min        | Mar 3                  | B         |
| 27      | Completing Development Part of Criteria C                | To have interesting parts of my code documented properly                                                                           | 2 hr          | Mar 3                  | C         |
| 28      | Coding: Beautifying Graphical User Interface             | To make the interface more user-friendly and easily understandable                                                                 | 2 hr          | Mar 3                  | C         |
| 29      | Filling Computational Thinking                           | To have the Computational Thinking part of Criteria C of the README file finished                                                  | 1 hr          | Mar 6                  | C         |
| 30      | Creating Test Plan                                       | To have a test plan created for confirming if the application works to standard                                                    | 1.5 hr        | Mar 7                  | C         |
| 31      | Consolidating and commenting code                        | To have the code finalized and organized for easy-understanding                                                                    | 1 hr          | Mar 7                  | C         |
| 32      | Beautifying README file                                  | To have README file consolidated and completed                                                                                     | 20 min        | Mar 7                  | B         |
| 33      | Finish video for Criteria D                              | Video evidence of all the success criteria functioning and working within the developed application                               | 10 min        | Mar 7                  | D         |




