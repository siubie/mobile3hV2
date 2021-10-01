#### Resume material week 4 by Ahmad Mahfudin Awi

# List View and Recycler View

## List View

In Android  development,  any time we want to show a vertical list of scrollable  items we will  use a LisView  which  has data populated using an Adapter

The simplest  adapter to use is called an ArrayAdapter  because  the adapter converts an ArrayList of objects into View items loaded  into the ListView  container.

### ListView Illustration

Data Source <--> Adapter <--> Adapter View

<ol>

<li> Data Source </li>

<ul> 

<li> Cursor </li>

<li> Array List </li>

</ul>

<li> Adapter </li>

<li> Adapter View </li>

<ul> 

<li> List View </li>

<li> Grid View </li>

<li> Spinner </li>

</ul>

</ol>

## Recycler View

RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView.

The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. 

The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's Layout Manager abstract class.