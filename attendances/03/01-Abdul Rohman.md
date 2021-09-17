<H1>Basic XML Layouts - Containers</H1><br>
Arguably, LinearLayout  is the most common modeling tool. It offers a "box" model similar to the Java-Swing  Box-Layout.<br>
Generally, complex UI designs result from the combination of simpler nested boxes that show their inner pieces using a horizontal or vertical orientation<br>

<H2>Basic XML Layouts - Containers</H2><br>
1. Android’s simplest layout manager is called: Frame Layout.<br>
2. A Frame Layout is a rectangular container that pins each child to its upper left corner.<br>
3. Adding multiple views to a frame layout just stacks one on top of the other (overlapping the views)<br>

<h3>Linear Layout</h3><br>
LinearLayout is a boLayout, you have five main areas of control besides the container's contents:<br>
1.orientation, <br>
----indicates whether the LinearLayout represents a row (HORIZONTAL) or a column (VERTICAL).
2.fill model, <br>
----Widgets have a "natural" size based on their accompanying text. <br>
----When their combined sizes does not exactly match the width of the Android device's screen, we may have the issue of what to do with the remaining space.<br>
3.weight, <br>
----It is used to proportionally assign space to widgets in a view.<br>
----You set android:layout_weight to a value (1, 2, 3, …) to indicates what proportion of the free space should go to that widget.<br>
4.gravity, <br>
----It is used to indicate how a control will align on the screen.<br>
----By default, widgets are left- and top-aligned.<br>
----You may use the XML property<br>
=>android:layout_gravity=“…”<br>
=>to set other possible arrangements:<br>
=>left, center, right, top, bottom, etc!<br>
5.padding ,<br> 
----The padding specifies how much space there is between the boundaries of the widget's "cell" and the actual widget contents.<br>
6. Margin<br>
----By default, widgets are tightly packed next to each other. <br>
----To increase space between them use the android:layout_margin attribute<br>
