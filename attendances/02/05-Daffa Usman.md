Activities and Intents
Activity is an application component. It represents one window, one hierarchy of views. An Activity handles user interactions, such as button clicks, text entry, or login verification. It can also start other activities in the same or other apps.
Activities are loosely tied together to make up an app. First activity user sees is typically called “main activity”. An activity typically has a UI layout, and its usually defined in one or more XML files.
Implementing new activities can be done by defining layout in XML, define activity java class, then connect activity with layout and declare activity in the android manifest.
Intent is a description of an operation to be performed. It is an object used to request an action from another app component via the Android system. Intent starts activities, services, and delivers broadcasts.
There are two types of intents, namely explicit intent (to start a specific activity) and implicit intent (to ask  system to find an activity that can handle this request).
Intent starts an activity by sending a message to the Android runtime to run an activity.
