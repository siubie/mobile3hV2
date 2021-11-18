Nama  : Rajendra Rakha Arya P

Kelas : 3H

---

### Summary Minggu Ke-6

1. How to install flutter on linux
2. Definition of flutter
3. Know about StatelessWidget and StatefullWidget

## What is Flutter

Flutter is an open source framework created by Google. Google created Flutter with the aim of building a framework to create a modern, native and reactive UI that can run on both iOS and Android operating systems. Not only on smartphones, Google also makes Flutter for desktop, web and embedded devices.

Flutter is programmed using Dart, a modern language that can
compiled to ARM processor architecture or javascript. Flutter using Skia 2D
rendering engine that can work on different hardware or software platforms.

Applications built using flutter have almost the same speed as native applications.

Dart also uses the concept of just-in-time (JIT) to allow programmers to make changes to the program code and immediately see the results through Flutter's hot reload feature.

## Widgets in Flutter


Flutter has two types of widgets namely **StatelessWidget** and **StatefullWidget**. 

- Stateless widget is used when the value (state / configuration) of the widget never changes. 

- StatefullWidget is used when the value (state / configuration) of the widget can change. 

**StatelessWidget and StatefullWidget** have a method called *build* which has a BuildContext to set the position of the widget in the widget tree.

## flutter project structure

1. .dart_tools : Configuration for dart language
2. .idea : Configuration for android studio
3. gitignore : A git file used to manage source code. This will be useful if the developer is already working with git.
4. metadata : File that contains metadata from the project
5. packages : Files containing path addresses
6. flutter_basic.iml: File containing details of the project.
7. pubspec.lock : File that contains the version of the library or package used in the degenerated project according to the pubspec.yaml file.
8. pubspec.yaml : File that contains libraries or packages needed for application development.
9. Readme.md : Markdown file that can be used to explain how to setup applications or important information that other developers need to know

## Flutter Hot Reload

Flutter has hot reload and hot restart functions which are used for application development with flutter. 

Hote reload compiles the newly added source code and sends it to the updated dart virtual machine. After the update is complete, the dart virtual machine will update the UI according to the changes.

## Flutter Hot Restart

Hot restart will recompile the application and reset (destroy) the existing state. So hot restart will rebuild the widget tree according to the updated code.