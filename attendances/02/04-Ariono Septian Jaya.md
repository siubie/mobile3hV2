## SUMMARY Week 2
   
 >   When we create Android applications, we can use software called android studio.
    Before the existence of android studio, the main pioneer was Eclipse.
    To create android applications, there are 2 programming languages ​​in Android Studio, namely Java and Kotlin.
    To run the program is not difficult, you can use a virtual device or from our cellphones
    (using a USB cable) / can also use mirroring to a laptop on our cellphone.
 
 >  In our Android studio there are provided components, namely Activity, Broadcast, Service, and Content.
    Activities are components that aim to display the screen so if you want to enter the other activity menu this is very helpful.
    Broadcast, which is a component that functions as a notification from other applications, for example, telephone, SMS OTP, etc.
    Next is Service which is a component which aims to carry out processes behind the scenes for example music play, GPS, sms receiver, etc.
    And the last one is Content where this component is managed from various sources.

   ### Summary of Commonly-used Android containers
        1. LinearLayout (the box model) LinearLayout is a view group that aligns all children in a single direction, vertically or horizontally. You can specify the layout direction with the [android:orientation] attribute
        2. RelativeLayout (a rule-based model) A RelativeLayout is a view group that displays child views in relative positions. The position of each view can be specified as relative to the sibling element (such as to the left or below another view) or in position relative to the parent RelativeLayout area (such as aligned to the bottom, left, or center).
        3. TableLayout (the grid model) TableLayout places its children into rows and columns. The TableLayout container does not display borders for its rows, columns, or cells. This table will have as many columns as the number of rows that have the most cells. Tables can leave cells blank. Cells can include multiple columns, as in HTML. You can expand columns using column spans in the TableRow.LayoutParams class.
        4. ScrollView, a container designed to assist with implementing scrolling containers.
        5. Others (ListView, GridView, WebView, MapView,…)

        ### Activities
    >An activity is a component of an application that represents a single window and a single hierarchy of views. Normally occupies the screen, however it can be integrated in other activities or appear as a floating window java class, with one activity per file.
    In terms of activity An action is something like ordering groceries, writing an email, or receiving directions. User interactions and a variety of other processes are handled by activities.

### Step To Implement Activities
    - Define layout in XML
    - Define Activity Java class
    - Connect Activity with Layout : Set content view in onCreate(). Parameter in setContentView is R.id.activity_main. Which is R is stand for Resource, layout is stand for layout, and activity_main is the xml file.
    - Declare Activity in the Android manifest.

### Intens
    An intent is a description of an operation to be performed. It is an object used to request an action from another app component via the Android system.
    - Explicit Intent
        Starts a specific activity
            Main activity starts the ViewShoppingCart activity
    - Implicit Intent
        Asks system to find an activity that can handle this request
            Find an open store that sells green tea
  