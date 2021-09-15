## ACTIVITIES AND INTENT

# A.	Activity
Activity is an application component. Represent one window, one hierarchy of view, nad can embedded in other activity or a appears as floating window.
1.	There are some point that activity can do:
a.	Represents an activity, such as ordering groceries, sending email, or getting directions
b.	Handles user interactions, such as button clicks, text entry, or login verification
c.	Can start other activities in the same or other apps
d.	Has a life cycle—is created, started, runs, is paused, resumed, stopped, and destroyed
2.	Step to implement new activities:
a.	Define layout XML
b.	Define Activity Java Class => extends AppCompatActivity
c.	Connect Activity with layout =>Set content view in onCreate()
d.	Declare Activity in the Android manifest

# B.	Intents
Intent is a description of an operation to be performed. Intent is an object used to request an action from another app component via android system. So intent use to move the activity to another activity.
1.	There are some point that intents can do:
a.	Start activity => A button click starts a new activity for text entry and clicking share opens an app that allows to post a photo
b.	Start service => initiate downloading a file in the background
c.	Deliver broadcast => the system informs everybody that the phone is now charging
2.	Explicit and Implicit Intents:
a.	Explicit Intent
Start a specific activity, Example : Request tea with milk delivered by Nikita => Main activity starts the ViewShoppingCart activity.
b.	Implicit Intent
Ask system to find an activity that can handle request, Example : Find an open store that sells green tea => clicking Share opens a chooser with a list of apps. So we can use intent to show web page, dial phone number, email, etc.
3.	Two type of sending data with intents:
a.	Data => one piece of information whose data location can be represented by an URL
b.	Extras => one or more pieces of information collection of key value pairs in bundle.
