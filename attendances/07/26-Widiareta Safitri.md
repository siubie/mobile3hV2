# Flutter Layouting

Material i have learn in one week is about layouting in flutter. During my learning, i found several code that still not familiar. For example:

### 1. SingleChildScrollView
SingleChildScrollView Widget a box that can scroll a single widget. When space is not enough, the widget inside can scroll on the spindle. If you need to shrink the package in two directions, such as the dialog or pop-up menu, in this case, the user can use SingleChildScrollView the child ListBody.

### 2. Expand
The Expanded widget in flutter is shorthand of Flexible with the default fit of FlexFit. Jadi ini akan membuat widget didalam row memenuhi semua ruang dalam row yang memiliki property expand

### 3. EdgeInsets.fromLTRB(1.0, 2.0, 3.0, 4.0)
This property will provide distance (margin or padding) but can be customized starting from left, top, right, bottom. so the distance can be changed easily.

### ElevatedButton
An ElevatedButton is a labeled child displayed on a Material widget whose Material. elevation increases when the button is pressed. The label's Text and Icon widgets are displayed in style's ButtonStyle.