<H1>ListView & RecyclerView</H1><BR>
<h2>ListView</h2><br>
- In Android development, any time we want to show a vertical list of scrollable items we will use a LisView which has data populated using an Adapter <br>
- The simplest adapter to use is called an ArrayAdapter because the adapter converts an ArrayList of objects into View items loaded into the ListView container.<br>
<h3>Array Adapter Code</h3><br>
  ArrayAdapter<String> itemsAdapter = 
    new ArrayAdapter<String>(this, android.R.layout.simple_list_item_1, items);
ListView listView = findViewById(R.id.lvItems);
listView.setAdapter(itemsAdapter);
  
<H3>Custom ArrayAdapter</H3><br>
 - Define the Model<br>
 - Create View Template<br>
 - Define the Adapter -> ArrayAdapter Inheritance <br>
 - Attaching the Adapter to a ListView <br>
 - Populating Data into ListView <br>
<H2>Recycler View<H2><br>
def $recyclerViewVersion = “1.2.0”
implementation "androidx.recyclerview:recyclerview:$recyclerViewVersion"
 - RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView.<br>
 - Each individual element in the list is defined by a view holder object. You define the view holder by extending RecyclerView.ViewHolder.<br>
 - The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter.<br>
 - The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class.<br>
<H3>Layout Manager</H3><br>
RecyclerView provides these built-in layout managers:<br>
 - LinearLayoutManager shows items in a vertical or horizontal scrolling list.<br>
 - GridLayoutManager shows items in a grid.<br>
 - StaggeredGridLayoutManager shows items in a staggered grid. <br>
<H3>Adapter</H3><br>
RecyclerView includes a new kind of adapter. It’s a similar approach to the ones you already used, but with some peculiarities, such as a required ViewHolder.You need to override three methods:<br>
 - onCreateViewHolder()
 - onBindViewHolder()
 - getItemCount()
