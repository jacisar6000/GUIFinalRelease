# Production Line Tracker
# GUIRelease Joseph Cisar, 12/7/2019

I have been hired to create software for a media player production facility that will keep track of what products are produced. 
Without the software, workers on the production floor are physically producing items and having to write down what is produced 
in a production log book. Management would like the production tracking to be more automated so the workers don't need to spend 
as much time recording what was produced, the log will be more accurate, and it will be easier to generate production reports. 

## JavaDocs Link: 
[JavaDocs](https://github.com/jacisar6000/GUIBetaProgram/blob/master/docs/index.html)

## GIF Demonstration
![](https://media.giphy.com/media/UShqYLej674bxsfJdd/giphy.gif)

## Software Used:
IntelliJ IDE, SceneBuilder, H2 Database

## Resources: 
Christian McCann, https://docs.oracle.com/javafx/2/ui_controls/combo-box.htm, 
https://noblecodemonkeys.com/how-to-use-observablelist-in-javafx-tutorial/, 
https://sites.google.com/site/profvanselow/course/cop-3003/oop-project

## Class Descriptions:

###### Audio Player
This file allows the application to show the user what the type of audio players are capable of extending product will implement the MultimediaControl class.

###### Controller
This file controls what the application is able to accomplish. It implements and initializes arrays, shows all of the objects and fx:id's that have been added tot he application, and allows the user to interact with the application but inputting and outputting informationMonitor into a database.

###### Employee
This class is set to create a new employee account and gives the employee a default email and username when the employees name is entered.

###### Item
This file allows the applications to retrieve the name and manufacturers of the items entered.

###### Item Type
This file allows the application to ItemTypes to be abbreviated for when they are shown in the observable array list it allows a more polished look for the user.

###### Main
This file allows the application to be ran and allows the application scene to be edited.

###### Monitor Type
This file allows the application to show the two different types of monitors.

###### Movie Player
This file allows the application to show different types of monitors, extend and implement other classes, show the user interactive options while viewing movies.

###### Multimedia Control
This file allows the user to play or stop music, and go to the next or previous song.

###### Product
This file allows the application to implements the item class, return specific information on the product such as its name, manufacturer, type of product, prints the product to the user and is the main driver behind the controller to edit the GUI.

###### Production Record
This file allows the application to take record of each product that is produced, its: serial number, ID, the date it was produced, and the number of products that have been produced. When used in the GUI the production record should show the information on any of the items entered into the database.

###### Sample
This file allows for the GUI to be ran and holds all of the specifications that were altered in SceneBuilder.

###### Screen
This file allows the application to show the user specifications of the screen by implementing screen specifications.

###### Screen Specification
This file allows the application to calls and return the screen specifications and return them to the screen.

###### Widget
This file allows the application to extend the product and enter the name, manufacturer, and type into the tableview.

