ListView
• In Android development, any time we want to show a vertical list of scrollable items we will use a LisView which has data populated using an Adapter
• The simplest adapter to use is called an ArrayAdapter because the adapter converts an ArrayList of objects into View items loaded into the ListView container.
How to use it?
• Using ArrayAdapter
• Using Custom ArrayAdapter
Example of using ArrayAdapter:
ArrayAdapter<String> itemsAdapter =
new ArrayAdapter<String>(this, android.R.layout.simple_list_item_1, items);
ListView listView = findViewById(R.id.lvItems);
listView.setAdapter(itemsAdapter);

Custom ArrayAdapter
• Define the Model
• Create View Template
• Define the Adapter -> ArrayAdapter Inheritance
• Attaching the Adapter to a ListView
• Populating Data into ListView

What is RecyclerView
• RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView.
• Each individual element in the list is defined by a view holder object. You define the view holder by extending RecyclerView.ViewHolder.
• The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter.
LayoutManagers
• RecyclerView provides these built-in layout managers:
• LinearLayoutManager shows items in a vertical or horizontal scrolling list.
• GridLayoutManager shows items in a grid.
• StaggeredGridLayoutManager shows items in a staggered grid.
Adapter
• RecyclerView includes a new kind of adapter. It’s a similar approach to the ones you already used, but with some peculiarities, such as a required ViewHolder.
