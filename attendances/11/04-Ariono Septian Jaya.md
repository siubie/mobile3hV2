Ariono Septian Jaya
TI 3H

Activity Defines an activity Starts a new activity with intent Passes data between activities with extras Navigates between activities

Activity (high level view) What is an Activity?

An activity is an application component Represents a single window, one view hierarchy Usually fills the screen, but can be embedded in other screens an activity or appears as a floating window Java classes, usually one activity in a file

What does the Activity do?

Represents an activity, such as ordering groceries, sending an email, or getting directions Handling user interactions, such as button clicks, text entry, or login verification Can initiate other activities in the same or another app Have a life cycle—created, initiated , run, pause, resume, stop and destroy

Apps and activities

Activities are loosely bound to build apps The first activity the user sees is usually called the "main activity" Activities can be set in parent-child relationships in the Android manifest to aid navigation

Layouts and Activities Activities typically have a UI layout Layouts are usually defined in one or more XML files Activity layouts "expand" as part of creation