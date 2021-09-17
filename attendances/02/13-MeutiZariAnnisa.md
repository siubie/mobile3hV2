# Android Activity And Intents

## Activity 
Activity is an application component that represents one window, one hierarchy of views.Typically, it fills with the screen, but can be embedded in other activity or a appear as floating window. Activity is in the form of Java class, typically one activity in one file

Activity represents an 'activity', such as ordering groceries, sending email, or getting directions. Activity is handle user interactions too, such as button clicks, text entry, or login verification. It can start other activities in the same or other apps. And it has a life cycle—is created, started, runs, is paused, resumed, stopped, and destroyed.

**About Activity and Apps**:
- Activities are loosely tied together to make up an app
- First activity user sees is typically called "main activity"
- Activities can be organized in parent-child relationships in the Android manifest to aid navigation

**About Activity and Layouts**:
- An activity typically has a UI layout
- Layout is usually defined in one or more XML files
- Activity "inflates" layout as part of being created

**How to implement new activity**:
1. Define layout in XML
2. Define Activity Java class 
<br>extends AppCompatActivity
3. Connect Activity with Layout
<br> Set content view in onCreate(). Parameter in setContentView is R.id.activity_main. Which is *R* is stand for Resource, *layout* is stand for layout, and activity_main is the xml file.
4. Declare Activity in the Android manifest

## Intents

An intent is a description of an operation to be performed. It is an object used to request an action from another app component via the Android system.

**What can intent do?**:
- Start activities
    - A button click starts a new activity for text entry
    - Clicking Share opens an app that allows you to post a photo
- Start services
    - Initiate downloading a file in the background
- Deliver broadcasts
    - The system informs everybody that the phone is now charging

**Explicit Intent**
- Starts a specific activity
    - Main activity starts the ViewShoppingCart activity


**Implicit Intent**
- Asks system to find an activity that can handle this request
    - Find an open store that sells green tea
    - Clicking Share opens a chooser with a list of apps

**Start an Activity with an explicit intent**
1. Create an intent
2. Use the intent to start the activity
<br>*Example*
    1. Show a web page
<br>Uri uri = Uri.parse("http://www.google.com");
<br>Intent it = new Intent(Intent.ACTION_VIEW,uri);
<br>startActivity(it);
    2. Dial a phone number
<br> Uri uri = Uri.parse("tel:8005551234");
<br>Intent it = new Intent(Intent.ACTION_DIAL, uri);
<br>startActivity(it);

**How Activities Run**
- All activities are managed by the Android runtime
- Started by an "intent", a message to the Android runtime to run an activity

**Sending and retrieving data**

*Sending activity:*
1. Create the Intent object
2. Put data or extras into that intent
3. Start the new activity with startActivity()

*Receiving activity:*
1. Get the intent object the activity was started with
2. Retrieve the data or extras from the Intent object

## Navigation 

- When a new activity is started, the previous activity is stopped and pushed on the activity back stack
- Last-in-first-out-stack—when the current activity ends, or the user presses the Back button, it is popped from the stack and the previous activity resumes

**Back navigation**

- Symbolized with triangle
- Back stack preserves history of recently viewed screens
- Back stack contains all the activities that have been launched by the user in reverse order for the current task
- Each task has its own back stack
- Switching between tasks activates that task's back stack
- Launching an activity from the home screen starts a new task
- Navigate between tasks with the overview or recent tasks screen

**Up navigation**
- Symbolized with arrow
- Goes to parent of current activity
- Define an activity's parent in Android manifest
- Set parentActivityName
<br> <br> <br>
# Android Basic XML Layouts

## Containers
Common used container:
- FrameLayout (simplest)
<br>Layout is a rectangular container that pins each child to its upper left corner. To add multiple views to a frame layout can just stacks one on top of the other (overlapping the views)

- LinearLayout (the box model), 
<br>LinearLayout is a box model – widgets or child containers are lined up in a column or row, one after the next. To configure a LinearLayout, you have five main areas of control besides the container's contents: 
    - orientation (Horizontal or Vertical)
    - fill model
    <br>All widgets inside a LinearLayout must supply dimensional attributes android:layout_width and android:layout_height to help address the issue of empty space. 

        Values used in defining height and width are:

        Specific a particular dimension, such as 125dip (device independent pixels)

        Provide wrap_content, which means the widget should fill up its natural space, unless that is too big, in which case Android can use word-wrap as needed to make it fit.

        Provide fill_parent, which means the widget should fill up all available space in its enclosing container, after all other widgets are taken care of.

    - weight, 
    <br>It is used to proportionally assign space to widgets in a view.

        You set android:layout_weight to a value (1, 2, 3, …) to indicates what proportion of the free space should go to that widget. 

    - gravity, 
    <br>It is used to indicate how a control will align on the screen. By default, widgets are left- and top-aligned.
    
        > Differences gravity and layout_gravity. Gravity is for the content and layout_gravity is for the view to parents.

    - padding 
    <br>The padding specifies how much space there is between the boundaries of the widget's "cell" and the actual widget contents. 

    - margin


- RelativeLayout (a rule-based model)
    <br>RelativeLayout places widgets based on their relationship to other widgets in the container and the parent container. 

    Position in this layout referring to the container:
    - **android:layout_alignParentTop** says the widget's top should align with the top of the container
    - **android:layout_alignParentBottom** the widget's bottom should align with the bottom of the container
    - **android:layout_alignParentLeft** the widget's left side should align with the left side of the container
    - **android:layout_alignParentRight** the widget's right side should align with the right side of the container
    - **android:layout_centerInParent** the widget should be positioned both horizontally and vertically at the center of the container
    - **android:layout_centerHorizontal **the widget should be positioned horizontally at the center of the container
    - **android:layout_centerVertical** the widget should be positioned vertically at the center of the container

    Position in this layout referring to the widget:
    - android:layout_above indicates that the widget should be placed above the widget referenced in the property 

    - android:layout_below indicates that the widget should be placed below the widget referenced in the property

    - android:layout_toLeftOf indicates that the widget should be placed to the left of the widget referenced in the property

    - android:layout_toRightOf indicates that the widget should be placed to the right of the widget referenced in the property

    - android:layout_alignTop indicates that the widget's top should be aligned with the top of the widget referenced in the property

    - android:layout_alignBottom indicates that the widget's bottom should be aligned with the bottom of the widget referenced in the property

    - android:layout_alignLeft indicates that the widget's left should be aligned with the left of the widget referenced in the property

    - android:layout_alignRight indicates that the widget's right should be aligned with the right of the widget referenced in the property

    - android:layout_alignBaseline indicates that the baselines of the two widgets should be aligned

- TableLayout (the grid model)
    1. Android's TableLayout allows you to position your widgets in a grid made of identifiable rows and columns.
    2. Columns might shrink or stretch to accommodate their contents. 
    3. TableLayout works in conjunction with TableRow. 
    4. TableLayout controls the overall behavior of the container, with the widgets themselves positioned into one or more TableRow containers, one per row in the grid.
    5. Rows are declared by you by putting widgets as children of a TableRow inside the overall TableLayout. 
    6. The number of columns is determined by Android ( you control the number of columns in an indirect way).
    7. By default, each column will be sized according to the "natural" size of the widest widget in that column.

        If your content is narrower than the available space,  you can use the TableLayout property:
	
	        android:stretchColumns =“…”

        Its value should be a single column number (0-based) or a comma-delimited list of column numbers. Those columns will be stretched to take up any available space yet on the row. 



- ScrollView, a container designed to assist with implementing scrolling containers. 

    When we have more data than what can be shown on a single screen you may use the ScrollView control.

    It provides a sliding or scrolling access to the data. This way the user can only see part of your layout at one time, but the rest is available via scrolling. 

    This is similar to browsing a large web page that forces the user to scroll up the page to see the bottom part of the form




