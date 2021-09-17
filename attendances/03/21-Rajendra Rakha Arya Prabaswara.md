Nama  : Rajendra Rakha Arya P
Kelas : 3H

---

### Summary Minggu Ke-3

In meeting 3, we discussed Widgets and Navigation in Android Studio.


### WIDGET

- A widget is a component that is created to build the UI appearance of an application. This widget is an inheritent or child of a class. There are many types of widgets in Android Studio, including:

1. TextView
2. Button
3. ScrollView
4. ImageView
5. etc

- In general, the User Interface (UI) hierarchy when creating Android applications is formed from a collection of layouts and widgets. These UI views are created using .XML files available for the Java and Kotlin programming languages. When you have created the view, it will be processed to set the value of a widget or retrieve the value from a widget using the Setter and Getter methods.

### Navigation

- Navigation is the process of moving from one screen to another in an application. In making navigation, you must know the direction of the next screen. Likewise, you must know which screen you are on before moving to another screen. Navigation Component is a library that is part of the Android Jetpack created to make it easier for developers to create navigation between Activities or Fragments. Previously in the navigation itself there were 3 principles:

- There's always starting place, which is the first screen that the user sees when opening an app for the first time and becomes the last screen when the user is about to close an app.
You can always Go back, namely the screen that we make must have a back function from the current destination to the start destination.
Up goes back, i.e. the Up button must have the same back function as the system back button. The up button is the button that we usually see in the upper left corner of an app, while the system back button is the button in the bottom right corner of an app or mobile phone.