
Layout Widget. 
The Layout Widget is a responsive container that allows you to separate a responsive container into sections.
Layouts can be placed inside the responsive containers of other layouts to create more even sections.

The core of Flutter’s layout mechanism is widgets. In Flutter, almost everything is a widget—even layout models are widgets. 
The images, icons, and text that you see in a Flutter app are all widgets. 
But things you don’t see are also widgets, such as the rows, columns, and grids that arrange, constrain, and align the visible widgets.
You create a layout by composing widgets to build more complex widgets

Most of this should look as you might expect, but you might be wondering about the containers (shown in pink). 
Container is a widget class that allows you to customize its child widget. 
Use a Container when you want to add padding, margins, borders, or background color, to name some of its capabilities.
In this example, each Text widget is placed in a Container to add margins. The entire Row is also placed in a Container to add padding around the row.
The rest of the UI in this example is controlled by properties. Set an Icon’s color using its color property. 
Use the Text.style property to set the font, its color, weight, and so on. 
Columns and rows have properties that allow you to specify how their children are aligned vertically or horizontally, and how much space the children should occupy.

How do you lay out a single widget in Flutter? This section shows you how to create and display a simple widget. It also shows the entire code for a simple Hello World app.

In Flutter, it takes only a few steps to put text, an icon, or an image on the screen.

1. Select a layout widget
Choose from a variety of layout widgets based on how you want to align or constrain the visible widget, as these characteristics are typically passed on to the contained widget.

2. Create a visible widget
For example, create a Text, Icon or Image widget:

3. Add the visible widget to the layout widget
All layout widgets have either of the following:
A child property if they take a single child—for example, Center or Container
A children property if they take a list of widgets—for example, Row, Column, ListView, or Stack.
Add the Text widget to the Center widget:

4. Add the layout widget to the page
A Flutter app is itself a widget, and most widgets have a build() method. Instantiating and returning a widget in the app’s build() method displays the widget.

