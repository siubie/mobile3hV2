1.	Linear Layout
LinearLayout is a box model – widgets or child containers are lined up in a column or row, one after the next.
To configure a LinearLayout, you have five main areas of control besides the container's contents: 
•	orientation, 
•	fill model, 
•	weight, 
•	gravity, 
•	padding ,
•	margin

1.1 	Linear Layout:  Orientation
indicates whether the LinearLayout represents a row (HORIZONTAL) or a column (VERTICAL).
1.2 	Linear Layout:  Fill Model
Widgets have a "natural" size based on their accompanying text. 
When their combined sizes does not exactly match the width of the Android device's screen, we may have the issue of what to do with the remaining space.
1.3 	Linear Layout:  Gravity
It is used to indicate how a control will align on the screen.
By default, widgets are left- and top-aligned.
You may use the XML property
	android:layout_gravity=“…”
	to set other possible arrangements:
	left, center, right, top, bottom, etc.

1.4 	Linear Layout:  Padding
The padding specifies how much space there is between the boundaries of the widget's "cell" and the actual widget contents. 
If you want to increase the internal whitespace between the edges of the and its contents, you will want to use the:
•	 android:padding property 
•	or by calling setPadding() at runtime on the widget's Java object.
Note: Padding is analogous to the margins on a word processing document.


	

