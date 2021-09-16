# Activities and Intents

## Activity
An Activity is an application component that represents one window, one hierarchy of views

What does an Activity do?
- Represents an activity, such as ordering groceries, sending email, or getting directions
- Handles user interactions, such as button clicks, text entry, or login verification
- Can start other activities in the same or other apps
- Has a life cycle—is created, started, runs, is paused, resumed, stopped, and destroyed

Layouts and Activities
- An activity typically has a UI layout
- Layout is usually defined in one or more XML files

## Intent
An intent is a description of an operation to be performed. An Intent is an object used to request an action from another app component via the Android system.

What can intents do?
- Start activities: a button click starts a new activity for text entry, clicking Share opens an app that allows you to post a photo
- Start services: initiate downloading a file in the background
- Deliver broadcasts: the system informs everybody that the phone is now charging

Explicit Intent
- Start a specific activity: 
- Example: MainActivity starts the ViewShoppingCart activity

Implicit Intent
- Asks system to find an activity that can handle this request
- Example: Clicking Share opens a chooser with a list of apps

## Starting Activities
- All activities are managed by the Android runtime, started by an "intent", a message to the Android runtime to run an activity
- To start a specific activity, use an explicit intent
- To ask Android to find an Activity to handle your request, use an implicit intent

## Sending and Receiving Data
Two types of sending data with intents
- Data: one piece of information whose data location can be represented by an URI
- Extras: one or more pieces of information as a collection of key-value pairs in a Bundle

## Navigation
When a new activity is started, the previous activity is stopped and pushed on the activity back stack

Two forms of navigation
- Temporal or back navigation: provided by the device's back button
- Ancestral or up navigation: provided by the app's action bar
