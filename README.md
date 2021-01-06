# TODO Application – What Are You Plans For The Day

## ABOUT
ToDo App is simple and awesome app to organize your tasks with very easy to use interface. ToDo can help you to make list of your tasks and also you can set a priority depending on how important is the task. The task with the highest priority is displayed at the top of the page and gradually show the task with lowest priority level.
A note taking app, using the Android Architecture Component libraries (`Room`, `ViewModel`, `LiveData`), Fragments, a RecyclerView and Java. The data will be stored in an SQLite database and supports `CRUD` operations.Together, this whole structure constitues an `MVVM (Model-View-ViewModel)` architecture, which follows the single responsibility and separation of concerns principles.



## Key Features of ToDo Application
-	User Friendly Task Management
-	Add unlimited todo tasks
-	Easily Modify the Task Heading / Description/ Priority as well as time
-	Easy swipe to delete task
-	Take notes to add to any task
-	accessible anywhere, on any android device

## To Do lists for any purpose

- Bill planner

- Shopping list

- Reminders

- Task management

- Take notes

- And more


## Working Methodology of Component of Android Architecture

**Entity**: When working with Architecture Components, this is an annotated class that describes a database table.

**SQLite database**: On the device, data is stored in an SQLite database. For simplicity, additional storage options, such as a web server, are omitted. The Room persistence library creates and maintains this database for you.

**DAO**: Data access object. A mapping of SQL queries to functions. You used to have to define these painstakingly in your SQLiteOpenHelper class. When you use a DAO, you call the methods, and Room takes care of the rest.

**Room database**: Database layer on top of SQLite database that takes care of mundane tasks that you used to handle with an SQLiteOpenHelper. Database holder that serves as an access point to the underlying SQLite database. The Room database uses the DAO to issue queries to the SQLite database.

**Repository**: A class that you create, for example using the WordRepository class. You use the Repository for managing multiple data sources.

**ViewModel**: Provides data to the UI. Acts as a communication center between the Repository and the UI. Hides where the data originates from the UI. ViewModel instances survive configuration changes.

**LiveData**: A data holder class that can be observed. Always holds/caches latest version of data. Notifies its observers when the data has changed. LiveData is lifecycle aware. UI components just observe relevant data and don't stop or resume observation. LiveData automatically manages all of this since it's aware of the relevant lifecycle status changes while observing.


#  APPLICATION FUNCTIONALITY
1. Adding a New ToDo Component

   New ToDo task can be easily added on to the application by clicking the floating button at the bottom of the application. Inside the activity you have various fields like Description, title, targeted date and priority of the task to be completed.
   ![](/screenshots/addtask.gif)

2. Update the existing ToDo Task

   So as to update the TODO task first simply click on the task you want to edit. Make the necessary changes and hit update to make change.
   ![](/screenshots/updatetask.gif)

3. Delete

   Deleting task can be easily achieved by simply swiping the finger right or left of the todo activity you choose to delete. 
   ![](/screenshots/deletetask.gif)