# ListView and RecyclerView

## ListView
ListView used to show a vertical list of scrollable items using Adapter.

There is a simplest adapter to use called ArrayAdapter.It  converts an ArrayList of objects into View items loaded into the ListView container.

**How To Custom ArrayAdapter**:
- Define the Model
- Create View Template
- Define the Adapter -> ArrayAdapter Inheritance
- Attaching the Adapter to a ListView
- Populating Data into ListView

## RecyclerView
RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView. 

Each individual element in the list is defined by a view holder object. We can define the view holder by extending RecyclerView.ViewHolder.

The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. We can define the adapter by extending RecyclerView.Adapter.

**Layout Manager**:
The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class.

Built-in layout manager:
- LinearLayoutManager shows items in a vertical or horizontal scrolling list.
- GridLayoutManager shows items in a grid.
- StaggeredGridLayoutManager shows items in a staggered grid.

**Adapter**:
RecyclerView includes a new kind of adapter. It’s a similar approach to the ones you already used, but with some peculiarities, such as a required ViewHolder. 

You need to override three methods:
1. onCreateViewHolder()
2. onBindViewHolder()
3. getItemCount()

