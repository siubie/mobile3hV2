Nama  : Rajendra Rakha Arya P

Kelas : 3H

---

### Summary Minggu Ke-8

## Stateless Widget

Stateless widget is static / final where the value or configuration has been initialized from the start, the variable value in this widget cannot be changed by this widget itself
but it can be changed by the parent widget if the parent is StatefullWidget

The basic structure of a stateless widget is as follows:

```java 
class exampleStateless extends StatelessWidget{
 @override
 Widget build(BuildContext context) {
 
 }
}
```

## Stateful Widget

Stateful widgets are dynamic, these widgets can be updated when needed accordingly
with user actions or if there is any data change. Data changes on statefull
widgets are triggered by state changes therefore a StatefullWidget always has a State

The basic structure of a statefull widget is as follows:

```java
class exampleStateless extends StatefulWidget{
 @override
 State<StatefulWidget> createState() {
 }
}
```

## List

Lists are collections like any other programming language. In the Dart programming language, an array is a list of objects, so it is also called a list. The following is an example of a list on Dart

``` dart
//contoh list of integer
var list = [1, 2, 3];
//contoh list of string
var list = [ 'Bike', 'Car', 'Bus', ];
```

