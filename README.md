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




![photo5](https://github.com/raja9492/Simple_to_do_list/assets/95007810/174feb3f-ee27-4431-a97e-f51c52e8bae9)





![photo4](https://github.com/raja9492/Simple_to_do_list/assets/95007810/d6faa245-6353-46f3-a4d8-329dd5662753)






![photo3](https://github.com/raja9492/Simple_to_do_list/assets/95007810/36885595-298d-4557-a01e-a8ff63426f56)





![photo2](https://github.com/raja9492/Simple_to_do_list/assets/95007810/38ab8a56-efc0-4dc1-a2f3-9d28d4a76961)





![photo1](https://github.com/raja9492/Simple_to_do_list/assets/95007810/d3602e83-9c4f-4b02-bbf7-c4eacd1388c8)


![photo6](https://github.com/raja9492/Simple_to_do_list/assets/95007810/a9251149-fcce-4e4c-afdb-2846586634ea)


