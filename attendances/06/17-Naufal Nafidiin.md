What is Widget ?
Widget is a description of a part of UI.
In flutter, Widget is a way to declare and construct UI.
If you are familiar with the Android or iOS development then you might make the immediate connection with the views (on Android) or UIViews (on iOS).
But dear just like view, Widget is not just a piece of UI. Widget is a lot more than just structural elements like buttons, text, image, list or slider. A widget might display Something, it might help define design, it might help with layout, it may handle user interaction, etc.
For example, Padding is a widget, Margin is a widget, Center is a widget, Layout rows and columns are also widgets.
So you can consider that a widget is a blueprint. Flutter uses these blueprints to create views.
Here also remember that in flutter everything is a widget. Even your app itself is a widget.

Widget tree
If you already have fun with flutter code then you might notice that infinite Parent-Child tree. Yaa I agree, first time it just scares out any beginner, but dear we all passes from the same stage in which you are right now. Just give it some time, do a lot of practice and Just believe, just like others, you can do it as well. 😉
Widgets are arranged into a tree of parent and child widget.
Widgets are nested inside of each other to form your app.
The Entire widget tree forms a layout that you see on the screen.

Types of Widgets
Now when we know what is a widget, its time to know how many types of widgets are there.
Flutter has a rich set of in-built widgets like text, buttons, slider, lists, layouts, gesture detector, animations, etc. Flutter team works really hard to create a set of widgets that helps you in almost every situation. And they are continuously adding more widgets as developers needs.
But apart from built-in widgets, you can create your own widgets according to your needs.
Flutter divides widgets into two categories:
Stateless Widgets
Stateful Widgets

Stateless Widgets
In simple words, if a widget doesn’t do anything its Stateless Widget. They are static in nature.
Stateless widgets don’t store any state. That means they don’t store values that might change.
You can also say that stateless widgets are “DATALESS” widgets. As they don’t store any real-time data.
For example, if you have a simple Text widget on the screen, but it doesn’t do anything then its Stateless Widget.
Icon, IconButton, and Text are an example of stateless widgets.

Stateful Widgets
In simple words, if a widget does anything then its Stateful Widget.
A Stateful widget is dynamic in nature. That means it can keep track of changes and update the UI based on those changes.
The user can interact with a stateful widget. For example, If you press a button and it performs any task its a Stateful Widget, If you are moving a slider and it does anything then its a Stateful Widget, If you swipe item from a list and item gets deleted then that list a Stateful Widget.
CheckBox, Radio, Slider, InkWell, Form, and TextField are an example of stateful widgets.
If you are in doubt, then always remember this rule. 😊
If a widget changes, it’s a Stateful Widget
If a widget is not changing, it’s a Stateless Widget.
