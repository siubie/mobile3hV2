<h1>List View & Recycler View</h1>
<h4>Hanum Aisyahqilla Algadrie / 1941720082</h4>

_________________________________________________________________________

<h3>List View</h3>
<p>In Android development, any time we want to show a vertical list of scrollable items we will use a LisView which has data populated using an Adapter. The simplest adapter to use is called an ArrayAdapter because the adapter converts an ArrayList of objects into View items loaded into the ListView container. </p>
_________________________________________________________________________

<h3>How to use List view?   </h3>
<p>1. Using Array Adapter </p>
<p>ArrayAdapter<String> itemsAdapter = 
    new ArrayAdapter<String>(this, android.R.layout.simple_list_item_1, items);
ListView listView = findViewById(R.id.lvItems);
listView.setAdapter(itemsAdapter); </p>
<p>2. Using Array Adapter</p>
<p>Define the Model, Create View Template, Define the Adapter -> ArrayAdapter Inheritance, Attaching the Adapter to a ListView, Populating Data into ListView </p>
________________________________________________________

<h3>Recycler View</h3>
<p>RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView. Each individual element in the list is defined by a view holder object. You define the view holder by extending RecyclerView.ViewHolder. The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter. The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class. </p>

<p>RecyclerView provides these built-in layout managers:
1. LinearLayoutManager shows items in a vertical or horizontal scrolling list.
2. GridLayoutManager shows items in a grid.
3. StaggeredGridLayoutManager shows items in a staggered grid.
</p>
_________________________________________________________________________


