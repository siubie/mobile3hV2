==Rangkuman w2==

=Activity=
-An Activity is an application component taht represents one window, one hierarchy of views and typically fills the screen, but can be embedded in other 
activity or a appear as floating window in java class, typically one activity in one file.

=Activity do=
-Represents an activity, such as ordering groceries, sending 
email, or getting directions
-Handles user interactions, such as button clicks, text entry, 
or login verification
-Can start other activities in the same or other apps
-Has a life cycle—is created, started, runs, is paused, 
resumed, stopped, and destroyed

=Apps=
-Activities tied together to make up an app
-user sees main activity
-Activities can be organized in parent-child relationships in 
the Android manifest to aid navigation

=Layouts=
-An activity typically has a UI layout. Layout is usually defined in one or more XML files.
-Activity "inflates" layout as part of being created

=How to Implement new activities=
-Define layout in XML
-Define Activity Java class 
    *extends AppCompatActivity
-Connect Activity with Layout 
    *Set content view in onCreate()
-Declare Activity in the Android manifest

=Intents=
-intent is a description of an operation to be performed. An Intent is an object used to request an action from another app component via the Android system.

what it do:
-Start activities
-Start services
-Deliver broadcasts

*Explicit:
-Starts a specific activity

*Implicit Intent :
-Asks system to find an activity that can handle this request

=Sending and Receiving Data=
*types:
-Data—one: one information data location can be represented by an URI 
-Extras—one: more pieces of information as a collection of key-value pairs in a Bundle

=Sending and retrieving data=
*send:
-Create the Intent object
-Put data or extras into the intent
-Start a new activity with startActivity()

*retriving:
-Get the intent object the activity was started with
-Retrieve the data or extras from the Intent object

=Navigation=
-When a new activity is started, the previous activity is stopped and pushed on the activity back stack
-Last-in-first-out-stack—when the current activity ends, or the user presses the Back button, it is popped from the stack and the previous activity resumes

*the two forms:
-Temporal or back navigation
-Ancestral or up navigation

*Back Navigation:
-Back stack preserves history of recently viewed screens
-Back stack contains all the activities that have been launched by the 
user in reverse order for the current task
-Each task has its own back stack
-Switching between tasks activates that task's back stack
-Launching an activity from the home screen starts a new task
-Navigate between tasks with the overview or recent tasks screen

*Up Navigation:
-Goes to parent of current activity
-Define an activity's parent in Android manifest



