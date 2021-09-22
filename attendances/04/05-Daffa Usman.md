Widget
Widget is main component to build UI in Android. It inherits from View class.
The user interface of an Android app is built as a hierarchy of layouts and widgets, which consists of ViewGroup and View class. 
Widgets wont be able to be manipulated with Java or Kotlin before we define the id in XML.
Navigation Component
Navigation between different screens and apps is a core part of the user experience. The following principles set a baseline for a consistent and intuitive user experience across apps.
The Navigation Component is designed to implement these principles by default, ensuring that users can apply the same heuristics and patterns in navigation as they move between apps.
Destination
Every built app must have a fixed start destination. It is the first screen the user sees when they launch your app from the launcher. It is also last screen the user sees when they return to the launcher after pressing the back button.
Navigation Graph
Destinations are the different content areas in your app, while actions are logical connections between your destinations that represent paths the user can take.
There are three components of Navigation Editor, namely Destinations panel, Graph editor, and attributes.
Destinations panel lists your navigation host and all destinations currently in the graph editor.
Graph editor contains a visual representation of your navigation graph. You can switch between Design view and the XML representation in the Text view.
Attributes shows the currently selected item’s attributes in the navigation graph.
One of the core parts of the Navigation component is the navigation host. It is an empty container where destinations are swapped in and out as a user navigates through your app. And it must be derived from NavHost.
