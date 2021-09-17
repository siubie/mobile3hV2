# Activities and Intent

# A. Activities

## Definition of Activity
- An Activity is an application component
- Represents one window, one hierarchy of views
- Typically fills the screen, but can be embedded in other activity or a appear as floating window
- Java class, typically one activity in one file

## What's does activity Do?
- Represents an activity, such as ordering groceries, sending
email, or getting directions
- Handles user interactions, such as button clicks, text entry,
or login verification
- Can start other activities in the same or other apps
-Has a life cycle—is created, started, runs, is paused,
resumed, stopped, and destroyed

## How to implement Activities in Java Mobile Programming?
1. Define layout in XML
2. Define Activity Java class
		- extends AppCompatActivity
3. Connect Activity with Layout
		- Set content view in onCreate()
4. Declare Activity in the Android manifest

# B. Intens

## Definition of Intens
An intent is a description of an operation to be performed.
An Intent is an object used to request an action from another
app component via the Android system.

## What's does activity Do?
- Start activities
-  A button click starts a new activity for text entry
-  Clicking Share opens an app that allows you to post a photo, ex: Start services
-  Initiate downloading a file in the background, ex: Deliver broadcasts
- The system informs everybody that the phone is now charging

## Explicit and implicit intents
1. Explicit Intent
● Starts a specific activity
○ Request tea with milk delivered by Nikita
○ Main activity starts the ViewShoppingCart activity
<br>
2. Implicit Intent
● Asks system to find an activity that can handle this request
○ Find an open store that sells green tea
○ Clicking Share opens a chooser with a list of apps