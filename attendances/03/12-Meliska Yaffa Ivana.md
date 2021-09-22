### Widget and Navigation
# A.	Widget
•	Widget is main component to build UI in Android
•	Widget inherits from View class
•	Check the palette in Android Studio for list of available UI Widget
1. 	UI Hierarchy
•	The user interface (UI) for an Android app is built as a hierarchy of layouts and widgets.
•	You need to define id in XML to manipulate Widget  using Java or Kotlin

2. 	Set/Get Value of Widget
•	It’s depends on Widget
•	EditText: Text etc
•	ImageView: ImageResource etc
•	RadioButton: Text, Checked
•	CheckBox: Text, Checked
•	Etc

# B.	Navigation Component
The navigation component is designed to implement these principles by default, ensuring that users can apply the same heuristics and patterns in navigation as they move between apps.
a.	Destination
•	Every app you build has a fixed start destination.
•	This is the first screen the user sees when they launch your app from the launcher. 
•	This destination is also the last screen the user sees when they return to the launcher after pressing the Back button.

b.	Navigation Graph
1.	Destinations are the different content areas in your app
2.	Actions are logical connections between your destinations that represent paths that users can take

c.	Navigation Editor
1.	Destinations panel: Lists your navigation host and all destinations currently in the Graph Editor.
2.	Graph Editor: Contains a visual representation of your navigation graph. You can switch between Design view and the underlying XML representation in the Text view.
3.	Attributes: Shows attributes for the currently-selected item in the navigation graph.

d.	Add NavHost into Activitity
•	One of the core parts of the Navigation component is the navigation host.
•	The navigation host is an empty container where destinations are swapped in and out as a user navigates through your app.
•	A navigation host must derive from NavHost

