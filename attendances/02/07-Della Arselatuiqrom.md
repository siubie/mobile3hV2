#Summary Week 2 :

Summary of Commonly-used Android containers :
-LinearLayout (the box model)

LinearLayout is a box model – widgets or child containers are lined up in a column or row, one after the next.

-RelativeLayout (a rule-based model)

RelativeLayout places widgets based on their relationship to other widgets in the container and the parent container. 

-TableLayout (the grid model)

Single widget can take up more than one column by including the android:layout_span property, indicating the number of  columns the widget spans (this is similar to the colspan attribute one finds in table cells in HTML)

-ScrollView, a container designed to assist with implementing scrolling containers.

When we have more data than what can be shown on a single screen you may use the ScrollView control. It provides a sliding or scrolling access to the data. This way the user can only see part of your layout at one time, but the rest is available via scrolling. 

-Misceellaneous Absolute Layout

Layout that lets you specify exact locations (x/y coordinates) of its children.Absolute layouts are less flexible and harder to maintain than other types of layouts without absolute positioning. 
