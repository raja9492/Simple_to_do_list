Here's a brief description of the project:

ToDoModel Class:

Represents a task with properties like id, status, and task.
DatabaseHandler Class:

Manages SQLite database operations for tasks.
Provides methods to insert, update, delete, and retrieve tasks.
ToDoAdapter Class:

Acts as an adapter for the RecyclerView in the MainActivity.
Binds the data from the database to the RecyclerView.
Handles checkbox state changes, task deletion, and task editing.
AddNewTask Class (BottomSheetDialogFragment):

Allows users to add or edit tasks using a bottom sheet dialog.
Communicates with the DatabaseHandler to perform database operations.
DialogCloseListener Interface:

Defines a method to handle the closing of the dialog.
RecyclerItemTouchHelper Class:

Implements ItemTouchHelper for swipe gestures on RecyclerView items.
Enables deleting or editing tasks through swipe actions.
MainActivity Class:

Sets up the main activity with a RecyclerView for displaying tasks.
Uses a FloatingActionButton to open the AddNewTask dialog.
Implements the DialogCloseListener interface to update the task list after dialog dismissal.
SplashActivity Class:

Displays a splash screen before launching the main activity.
Instructions to Set Up and Run the Application:
Dependencies:

Ensure you have the necessary dependencies and permissions set up in your Android project, including the necessary libraries and resources.
Database Setup:

The SQLite database is managed by the DatabaseHandler class. Ensure that the necessary tables are created by running the onCreate method.
Activity Configuration:

Update the AndroidManifest.xml file with the necessary activities, permissions, and configurations.
Layout Files:

Create the necessary layout files (task_layout.xml, new_task.xml, etc.) for the UI components used in the application.
Drawable Resources:

Ensure the necessary drawable resources (e.g., ic_baseline_edit and ic_baseline_delete) are available in the res/drawable folder.
Run the Application:

Build and run the application on an Android emulator or a physical Android device.
Usage:

Launch the app, and you should see a list of tasks.
Use the FAB button to add new tasks.
Swipe left to delete tasks, or swipe right to edit tasks.
Task updates are reflected in real-time.



![photo1](https://github.com/raja9492/Simple_to_do_list/assets/95007810/1cb01747-d1cb-4306-b73c-5479a759d73c)


![photo2](https://github.com/raja9492/Simple_to_do_list/assets/95007810/56a70859-fb47-4afa-8558-1d479c941efb)

![photo3](https://github.com/raja9492/Simple_to_do_list/assets/95007810/79118098-9ed3-4744-b6d4-23257b7d94fa)

![photo4](https://github.com/raja9492/Simple_to_do_list/assets/95007810/b9003e8e-b5a7-4c6f-bffc-aa9af11aedef)

![photo5](https://github.com/raja9492/Simple_to_do_list/assets/95007810/642faf61-7c02-4d86-886a-703c2c425ed1)



![photo6](https://github.com/raja9492/Simple_to_do_list/assets/95007810/ded1ebd7-ea9c-4bf4-aefb-5a3b3d5b7aa9)







