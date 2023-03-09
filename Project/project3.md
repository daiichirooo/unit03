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

## Record of Tasks

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
| 22      | Creating System Diagram                                  | To explain how the system works                                                                                                   | 30 min        | Mar 7                  | B         |
| 23      | Creating UML Diagram                                     | To explain about the class and function                                                                                                   | 30 min        | Mar 7                  | B         |
| 24      | Creating ER Diagram                                      | To explain how the database works                                                                                                    | 30 min        | Mar 7                  | B         |
| 25      | Creating Flow Diagrams                                   | To explain some codes that I worked on                                                                                                | 30 min        | Mar 7                  | B         |
| 26      | Completing Development Part of Criteria C                | To explain all the codes that I worked on                                                                           | 3 hr          | Mar 8                  | C         |
| 27     | Finish video for Criteria D                              | To show the result of the application that I made                               | 10 min        | Mar 9                  | D         |



## Flow Diagrams
**Password Verification System**
![](fd1.png)
Fig.5 Flow diagram of a Password verification system.

**Delete Function**
![](fd2.png)
Fig.6 Flow diagram of Delete function.

**Add Function**
![](fd3.png)
Fig.7 Flow diagram of Add function.



## Test Plan ##
| Type                | Description                 | Process                                                                                                                                                                                                                                                                                      | Anticipated Outcome                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Unit Testing        | User Registration           | 1. Run project3_main.py <br />2. Click the Signup button on the StartScreen <br />3. Input the certain information(username, email, password, Confirm password) in each textfield<br /> 4. Click Register                                                                                         | After clicking the register button, if all text fields are blank, the text fields turn red to inform the user that input is required. If the username already exists, the user is informed of this fact and told that they need to change it to another username. If the email was not formatted correctly, the user is asked to rewrite the email. They are then asked to reconfirm their password and confirmation password if they do not match. When all text fields meet the criteria, the user can proceed to the LoginScreen. |
| Unit Testing        | User Login                  | 1. Run project3_main.py <br />2. Click the Login button on the LoginScreen <br /> Input the certain information(username,and password) in each textfield<br /> 4. Click Login                                                                                                                                                         | After clicking the login, if all text fields are blank, the text fields turn red to inform the user that input is required. If the username does not exist, the user is informed of this fact and that they need to change it to a username that does exist. The user is then asked to reconfirm the password if it does not match. When all text fields have been met, the user can proceed to the HomeScreen.                                                                                                                                                          |
| Unit Testing        | Logout                      | 1.Click the Logout button on the HomeScreen                                                                                                                                                                                                                                                   | The app should logout immediatly and go back to the StartScreen.                                                                                                                                                                                                                                                                                                                                                                                                            |
| Integration Testing | Login and Registration and Logout   | 1. Run project3_main.py <br />2. Click the Signup button on the StartScreen<br /> 3. Input the certain information(username, email, password, Confirm password) in each textfield <br />4. Click Register and go to the LoginScreen<br />5. Input the certain information(username,and password) in each textfield  <br /> 5.Click Login   <br /> 6.Click the Logout button on the HomeScreen                    | This sequence of signing up, logging in, and logging out can proceed without error if the user follows the instructions closely.                                                                                                                                                                                                                                                                                               |
| Unit Testing        | Adding food           | 1. Run project3_main.py <br />2. Login with the userid and password <br />3. Click "Add" button on the HomeScreen <br />4. Input certain informations(fooditem, amount) on the textfields.<br />5. Click the place button(Fridge1, Fridge2, Room) <br />6. Click the "Expiration date" button and select the expiration date of the food <br />7. press "Add" button to add the food on the list                                                                                                                | If the food_item text field is empty, the text field turns red to inform the user that input is required. If the food_amount text field is empty, the text field turns red to inform the user that input is required. The food can then be added to the list by pressing the button for the place where the food is stored and selecting an expiry date.                                                                                                                                  |
| Unit Testing        | See the list         | 1. Run project3_main.py <br />2. Login with the userid and password <br />3. Click "List" button on the HomeScreen <br />4. Click the button (Fridge1, Fridge2, Room, All) to select the foods which is stored in each location <br />5. Click the check button on the list, click "Delete button" on the bottom bar<br /> 6.Click the check button on the list, click the row that you want to change, input the texts about the amount of the food, and click "Change button" on the bottom bar.                                                        | If you press the buttons (Fridge1, Fridge2, Room, All) and the food stored only in the respective location will appear in the list.                                                                                                                               |
| Unit Testing        | Deleting Vocabulary         | 1. Run project3_main.py <br />2. Login with the userid and password <br />3. Click the check button on the list<br /> 4. Click "Delete button" on the bottom bar | If no tick button on the list has been pressed, the user is informed that the tick button needs to be pressed. If more than one tick button in the list has been pressed, the user is informed that only one tick button needs to be pressed. The item is then deleted by pressing the delete button.         |
| Unit Testing        | Editing amount Vocabulary      | 1. Run project3_main.py <br />2. Login with the userid and password <br />3. Click "List" button on the HomeScreen <br />4.Click the check button on the list. <br />5.Click the row that you want to change. <br />6.input the texts about the amount of the food. <br />7.and click "Change button" on the bottom bar.                                                       | The application changes the amount of food at the moment the change button is pressed, with the text put in by the user being entered into the row chosen by the user.                                                                                                                                                                                                                                                                                |
| Integration Testing | Adding + Editing Vocabulary | 1. Run project3_main.py <br />2. Login with the userid and password <br />3. Add a food <br />4. press the "list" button to go to the ListScreen <br />5.Click the button(Fridge1, Fridge2, Room, All)to see each food.<br />6.delete the food. <br />7.change the amount of food. <br />8. Press the button "Home" to go HomeScreen                                                                                                    | If the user uses these functions in a suitable way, they can be used without any errors. By using the application you will be able to view the list, change the contents of the list, delete the contents of the list, etc.                                                                                                                                                                                                                                                                                                    |
| Code Review         | Reviewing Code              | Going through the code and making sure all the codes are working                                                                                                                                                           | If there is an error or any problems, I will fix it.                                                                                                                                                                                                                                                                                                                           |


# Criteria C: Development

## Exisisting tools

| Software/Development Tools | Coding Structure Tools       | Libraries  |
|----------------------------|------------------------------|------------|
| PyCharm                    | OOP Structures(Classes)      | Kivymd.app |
| Python                     | SQL requests                 | Passlib    |
| KivyMD                     | Databases                    | sqlalchemy |
| SQLite                     | Encryption                   | kivymd.uix |
| Github Copilot             | For Loops                    |            |
| ChatGPT                    | If-then-else statements      |            |
|                            | ORM(Object Relation Mapping) |            |

## List of techniques used

1. Object Oriented Programming(OOP)
2. Object Relation Mapping(ORM)
3. KivyMD Library
4. For loops
5. if statements
6. Hashing (password)
7. Databases

## Computational Thinking

### Decomposition
In computational thinking, decomposition refers to dividing a complex problem or system into parts that are easier to conceptualize, understand, program, and maintain. A key aspect of this project was a scoring system for storing statistics and user performance in a database. This requires multiple steps, so I split the overall action into gathering user and vocabulary information, calling another function in the database handler, and moving the GUI to the next card. This is a snippet of the add points function. 

## Development

### KyvyMD

#### Screen Manager
```.kv
ScreenManager:
    id:scr_manager
    StartScreen:
        name: "StartScreen"
    LoginScreen:
        name: "LoginScreen"
    SignupScreen:
        name: "SignupScreen"
    HomeScreen:
        name: "HomeScreen"
    AddScreen:
        name: "AddScreen"
    ListScreen:
        name: "ListScreen"
```
Clients need the application to record and store the food they have. To meet these expectations, they are going to use KyvyMD's ScreenManager to manage the pages of the interface they develop. The ScreenManager widget serves as the basis for the user interface of the multi-screen application. The ScreenManager is given the ID scr_manager.

The ScreenManager is responsible for managing multiple screens in the UI. In my application, six screens are defined within the ScreenManager, each with a unique name. (StartScreen, LoginScreen, SignupScreen, HomeScreen, Addscreen, ListScreen) Each screen is defined as a custom widget and is specified by its class name.

LoginScreen and SignupScreen are screens for users to authenticate and create new accounts respectively; HomeScreen acts as the main screen of the application and typically allows users to use various services. The AddScreen allows users to add new food information to their account, while the ListScreen displays a list of food items stored by the user.


#### MDBoxLayout
```.kv
MDBoxLayout:
        size_hint: .7, .7
        orientation: "vertical"
        pos_hint:{"center_x":.5,"center_y":.5}
```
MDBoxLayout is a type of layout in the KivyMD library which arranges child widgets either vertically or horizontally. It is a subclass of the BoxLayout in the Kivy framework.

In this code, the MDBoxLayout is created with a size_hint of .7, .7, which means it will take up 70% of the available space in both the horizontal and vertical directions. The orientation is set to "vertical", which means the child widgets will be stacked vertically. Finally, the pos_hint sets the position of the MDBoxLayout at the center of the parent widget.

To use MDBoxLayout, you need to import it from the KivyMD library and add child widgets to it. The child widgets can be added in the kv language or in Python. You can also set the size and position of the child widgets using various properties like size_hint, size, and pos_hint.

#### MDRaisedButton
```.kv
MDRaisedButton:
                id: try_login_button
                size_hint: .5, 1
                text: "Login"
                md_bg_color: "#c56e33"
                on_press: root.parent.current = "LoginScreen"
```
MDRaisedButton is a button widget in the KivyMD library that is designed to have a raised appearance. It inherits from the Button widget in the Kivy framework and adds extra styling to make it look like a raised button.

In this code, the MDRaisedButton is created with an id of try_login_button. The size_hint is set to .5, 1, which means the button will take up half of the available horizontal space and all of the available vertical space. The text property sets the text of the button to "Login". The md_bg_color sets the background color of the button to "#c56e33", which is a shade of brown. Finally, the on_press event sets the current property of the parent widget to "LoginScreen" when the button is pressed.

To use MDRaisedButton, you need to import it from the KivyMD library and create an instance of it in your code. You can then add it to your app's layout like any other widget.

#### Images
```.kv
Image:
            id: logo
            size_hint: 1, 1
            source: "logo_clear.png"
            halign: "center"
            pos_hint:{"center_x":.5,"center_y":.5}
```
In KivyMD, the Image widget is used to display images in your application. It is a subclass of the AsyncImage widget in Kivy and provides additional features such as the ability to scale and align the image.

In the code, an Image widget is created with an id of logo. The size_hint is set to 1, 1, which means the image will take up all available space. The source property sets the path to the image file that will be displayed. The halign property sets the horizontal alignment of the image to the center, and the pos_hint property centers the image in its parent widget.

To use Image in your KivyMD app, you first need to import it from the KivyMD library. Then, you can create an instance of it and set its properties, just like any other widget.


#### MDCard
```.kv
MDCard:
        size_hint: 0.5, .9
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y": .5}
        padding: dp(50)
```
MDCard is a widget in the KivyMD library that provides a Material Design card component. The card is typically used to group related information and actions together in a user interface.

The widget has several properties that can be customized, such as size_hint, which determines the size of the card relative to its parent widget, and pos_hint, which specifies the card's position relative to its parent widget using a dictionary of normalized position values. The elevation property sets the visual depth of the card, with higher values creating a stronger drop shadow effect. The padding property determines the amount of space between the edge of the card and its contents.

The orientation property sets the layout orientation of the card's contents. By default, it is set to "vertical", which means that the contents will be arranged vertically from top to bottom. However, it can also be set to "horizontal" to arrange the contents horizontally from left to right.

To use MDCard in your KivyMD app, you need to import it from the KivyMD library and create an instance of it, setting its properties as desired. You can then add the card to your app's user interface hierarchy, typically inside a container widget like a BoxLayout or GridLayout.

#### MDlabel
```.kv
MDLabel:
                text: "Place"
                font_size: 40
                size_hint: .6, .05
                pos_hint: {"center_x": .5, "center_y": .5}
```
MDLabel is a widget in the KivyMD library that displays text in a user interface. It is similar to the standard Kivy Label widget, but provides additional features and styling options specific to the Material Design language.

The widget has several properties that can be customized, such as text, which sets the label's text content, and font_size, which sets the size of the text. Other properties include size_hint, which determines the size of the label relative to its parent widget, and pos_hint, which specifies the label's position relative to its parent widget using a dictionary of normalized position values.

To use MDLabel in your KivyMD app, you need to import it from the KivyMD library and create an instance of it, setting its properties as desired. You can then add the label to your app's user interface hierarchy, typically inside a container widget like a BoxLayout or GridLayout.

In this code, text is set to "Place", font_size is set to 40, size_hint is set to .6 for width and .05 for height, and pos_hint is set to center the label horizontally and vertically within its parent widget. These settings are specific to the example code and can be adjusted to suit the needs of your app.

#### MDtextfield
```.kv
MDTextField:
            id: login_userid_input
            hint_text: "Enter your username or email"
            icon_left: "email"
            size_hint: 1, .1
            helper_text_mode: "on_error"
            on_text: root.userid_empty()
            helper_text: ""
            required: False
```
MDTextField is a widget in the KivyMD library that allows users to input text. It is similar to the standard TextInput widget in Kivy, but has additional features and styling options. The widget has several properties that can be customized, such as hint_text, which displays a hint to the user when the field is empty, and icon_left and icon_right, which allow you to add icons to the left or right side of the text field.

Other properties include size_hint, which determines the size of the field relative to its parent widget, and helper_text_mode, which controls when helper text is displayed. on_text is a method that is called whenever the text in the field changes, while helper_text can be used to display additional text alongside the main text field, such as an error message or instructions for the user.

Finally, required is a boolean property that determines whether the field is required to be filled in by the user. To use MDTextField in your KivyMD app, you need to import it from the KivyMD library and create an instance of it, setting its properties as desired.

#### MDChip
```.kv
MDChip:
                    text: "Room"
                    icon_left: "bed-outline"
                    size_hint: .3, .8
                    on_press: root.on_chip_pressed(self)
                    on_active: if self.active: root.removes_marks_all_chips(self)
```
MDChip is a widget in the KivyMD library that displays information in a compact, clickable format. It is often used to display tags or categories that users can select or interact with. The widget has several properties that can be customized, such as text, which displays the main text of the chip, and icon_left and icon_right, which allow you to add icons to the left or right side of the chip.

Other properties include size_hint, which determines the size of the chip relative to its parent widget, and on_press, which is a method that is called when the chip is clicked. The on_active property can be used to specify a method that is called when the chip's state changes, such as when it is selected or deselected.

In this code, on_chip_pressed and removes_marks_all_chips are methods defined in the parent widget that are called when the chip is pressed or its state changes, respectively. These methods can be used to update the state of the app or perform other actions based on the user's interaction with the chip.

To use MDChip in your KivyMD app, you need to import it from the KivyMD library and create an instance of it, setting its properties as desired. You can then add the chip to your app's user interface hierarchy, typically inside a container widget like a BoxLayout or GridLayout.
