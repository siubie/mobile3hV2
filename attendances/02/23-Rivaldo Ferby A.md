Basic XML Layouts – Containers
1.Commonly-used Android containers

1. LinearLayout (the box model) : LinearLayout is a box model – widgets or child containers are lined up in a column or row, one after the next.
2. RelativeLayout (a rule-based model) : RelativeLayout places widgets based on their relationship to other widgets in the container and the parent container.
3. TableLayout (the grid model) : allows you to position your widgets in a grid made of identifiable rows and columns.
4. ScrollView, a container designed to assist with implementing scrolling containers when we have more data than what can be shown on a single screen you may use the ScrollView control.
   It provides a sliding or scrolling access to the data. This way the user can only see part of your layout at one time, but the rest is available via scrolling.
5. Other (ListView, GridView, WebView, MapView,…)

2.What is an activity
● An Activity is an application component
● Represents one window, one hierarchy of views
● Typically fills the screen, but can be embedded in other activity or a appear as floating window 3. What does an Activity do?
● Represents an activity, such as ordering groceries, sending email, or getting directions
● Handles user interactions, such as button clicks, text entry, or login verification
● Can start other activities in the same or other apps 4. Apps and activities  
● Activities are loosely tied together to make up an app
● First activity user sees is typically called "main activity"
● Activities can be organized in parent-child relationships in the Android manifest to aid navigation 5. Layouts and Activities
● An activity typically has a UI layout
● Layout is usually defined in one or more XML files
● Activity "inflates" layout as part of being created
6.What is an intent?
An intent is a description of an operation to be performed. An Intent is an object used to request an action from another app component via the Android system. 7. What can intents do?
● Start activities : A button click starts a new activity for text entry,Clicking Share opens an app that allows you to post a photo
● Start services : Initiate downloading a file in the background
● Deliver broadcasts : The system informs everybody that the phone is now charging
8.Explicit and implicit intents Explicit Intent
● Starts a specific activity : Request tea with milk delivered by Nikita, Main activity starts the ViewShoppingCart activity Implicit Intent
● Asks system to find an activity that can handle this request : Find an open store that sells green tea,Clicking Share opens a chooser with a list of apps 9. Activity stack
● When a new activity is started, the previous activity is stopped and pushed on the activity back stack
● Last-in-first-out-stack—when the current activity ends, or the user presses the Back button, it is popped from the stack and the previous activity resumes
