<H2>Today material is about Basic Layout</H2> <br>
<h3>Summary of Commonly-used Android containers</h3> <br>  
1.LinearLayout (the box model),<br>
 => LinearLayout is a box model – widgets or child containers are lined up in a column or row, one after the next.<br>
2.RelativeLayout (a rule-based model),<br>
 => RelativeLayout places widgets based on their relationship to other widgets in the container and the parent container. <br>
3.TableLayout (the grid model), <br>
 => Android's TableLayout allows you to position your widgets in a grid made of identifiable rows and columns.<br>
4.ScrollView, <br>
 => a container designed to assist with implementing scrolling containers.<br>
5.Other (ListView, GridView, WebView, MapView,)<br>

<br>● Activities are loosely tied together to make up an app
<br>● First activity user sees is typically called "main activity"
<br>● Activities can be organized in parent-child relationships in the Android manifest to aid navigation

<br>● An activity typically has a UI layout
<br>● Layout is usually defined in one or more XML files
<br>● Activity "inflates" layout as part of being created

<h2>Step to implement Layout</h2><br>
1. Define layout in XML<br>
2. Define Activity Java class<br>
○ extends AppCompatActivity<br>
3. Connect Activity with Layout<br>
○ Set content view in onCreate()<br>
4. Declare Activity in the Android manifest<br>

<h2>Activity Stack</h2><br>
● When a new activity is started, the previous activity is stopped and pushed on the activity back stack <br>
● Last-in-first-out-stack—when the current activity ends, or the user presses the Back button, it is popped from thestack and the previous activity resumes <br>
