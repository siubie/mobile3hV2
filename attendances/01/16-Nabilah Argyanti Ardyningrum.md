# Android Fundamentals
Android: 
- Software stack for mobile devices. 
- SDK provides tools and APIs to develop apps

Application
- Ships with core set of apps, written in Java
- Developers have access to core APIs: Views, content providers, resource manager, notification manager, activity manager

Main components of Android
- Activities: Single page user interface, most apps have multiple activities
- Services: No user interface, runs in background, started and stopped by activities
- Content Providers: Manages shared set of application data, data may be shared between apps or be private
- Broadcast Receivers: Listens for system wide (intent) broadcasts, intent filter limits which intents cared about

Intents
- Allows an activity, service or broadcast receiver to link to another within or between apps

UI Basics
- Recall activity
- An Activity displays the user interface
- User Interfaces are built from View and ViewGroup object instances of the View class
- View objects are data structures that store content and layout parameters 
- Subclass  “widgets” provide user interface objects: text fields, buttons, labels

View & ViewGroup
- ViewGroup objects act like containers for View objects
- Subclass “layouts” provide different layout architectures: LinearLayout, RelativeLayout, TableLayout, AbsoluteLayout, FrameLayout, ScrollView

View Hierarchy

![image](https://user-images.githubusercontent.com/56666206/132606032-5f3b02b1-8325-4eb6-bbe2-437b37076dd7.png)
- Parent nodes contain and organize layout of child nodes
- Child nodes are responsible for drawing themselves at the request of the parent
- The Activity that displays a particular screen calls the setContentView() method to draw the screen defined by the hierarchy
- XML layout files typically used for defining layouts and expressing view hierarchies

Input Events
- Define to inform the system of user interaction
- Event listener is defined  and registered with the View object 
- View class has a collection of On<SomeEvent>Listener: View.OnClickListener, View.OnTouchListener, View.OnKeyListener
- Example: OnTouch, when the user touches a defined View object on the screen, define View.OnTouchListener
  
Application Menus
- Type: Option menu (when app running), Context menu (display information)
