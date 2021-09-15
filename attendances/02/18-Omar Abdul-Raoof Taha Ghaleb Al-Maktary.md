In today's class, we learned about activities. An Activity is an application component. We also learned about intent. 
An intent is a description of an operation to be performed. An Intent is an object used to request an action from another app component via the Android system.
We also learned about Android MVVM, MVVM stands for Model, View, ViewModel.

Model: This holds the data of the application. It cannot directly talk to the View. Generally, it’s recommended to expose the data to the ViewModel through Observables.
View: It represents the UI of the application devoid of any Application Logic. It observes the ViewModel.
ViewModel: It acts as a link between the Model and the View. It’s responsible for transforming the data from the Model. It provides data streams to the View. It also uses hooks or callbacks to update the View. It’ll ask for the data from the Model.

Basic XML Layouts - Containers:
Linear Layout
Relative Layout 
Table Layout
ScrollView Layout
Miscellaneous Absolute Layout
