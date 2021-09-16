ACTIVITIES AND INTENTS
    Activity is an application component. Activity can represents an activity, such as ordering groceries, sending
email, or getting directions. activity are loosely tied together to make up an app and activities can be organized in parent-child relationships
in the android manifest to aid navigation. Layout of activities has a UI layout, layout usually defined in one or more XML file.
Activities can be implemented by define layout in XML, Define activity java class, connect activity with layout, and declare activity in android
manifest.
  Intent is a object used to request and action from another app component via android system.
Intent can start activites, start services, deliver broadcasts. Intent divide into 2 parts Explicit Intent and Implicit intent.
-Explicit Intent: Starts a specific activity, for example Request tea wiith milk delivered by Nikita
-Implicit Inten : Ask system to find an activity that can handle this request, for example find an open store that sells green tea.
Intents have a two data type of sanding a data: 
- Data one piece of information whose data location can be represented by an URL.
- Extras one or more pieces of information as a collection of key value in a bundle.
  Navigation when a new activity is started, the previous activity is stopped and pushed on the activity back stack. Navigation have a two forms: 
- Temporal or black naviigation provided by the device's back button, and controlled by the android system's back stack
- Ancestral or up navigation provided by the app's action bar, and controlled by defining parent child relationship between activities in the android manifest.
