Nama  : Rajendra Rakha Arya P

Kelas : 3H

---

### Summary Minggu Ke-9

### NAVIGATION DAN ROUTE 

## Navigator
This widget that manages the stack (stack data structure) of the route object

## Routes
An object that represents a view, generally implemented by a class such as MaterialPageRoute

## Define Route

The route naming definition must be unique. The HomePage page is defined as /.
And the ItemPage page is defined as /item. To define the start page, you can use the named argument initialRoute.

## Switch Pages

Page switching in Flutter, handled by Navigator involving concepts
as follows:

- Navigator: a widget that manages the stack (stack data structure) of objects
route
- Route: an object that represents a view, generally implemented by a class such as MaterialPageRoute

**A Route** is generally inserted (push) or taken (pop) from and to the stack
Navigator. 

- When a page is **pushed** the page will be placed on top of the page that called it.

- When a page is **pop** is called (back button pressed) then the app will display the previous page.

Flutter also supports naming The route defined at the beginning.

## Simple Routing Flutter

```
Navigator.push(
    context, 
   	MaterialPageRoute(builder: (context) {
  		return AboutPage()
  	})
);
```