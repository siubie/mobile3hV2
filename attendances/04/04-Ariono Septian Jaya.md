## TI3H-04-Ariono Septian Jaya

### Meeting Summary 4

# This week discusses List View and Recycle View

In Android development, whenever we want to display a scrollable vertical list of items, we will use a ListView which has data populated using an Adapter. The simplest adapter to use is called an ArrayAdapter because it converts an ArrayList object into a View item that is loaded into a ListView container.

RecyclerView is a ViewGroup that renders adapter-based views in a similar way. And should be the successor to ListView and GridView.

Each individual element in the list is defined by the view holder object. Defines a view holder by extending RecyclerView.ViewHolder.

The RecyclerView requests the view, and binds the view to its data, by calling a method in the adapter. You define an adapter by extending RecyclerView.Adapter.

The layout manager organizes the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. The layout managers are all based on the library's LayoutManager abstract class.

LayoutManager RecyclerView provides this built-in layout manager:

LinearLayoutManager displays items in a vertical or horizontal scrolling list.
GridLayoutManager displays items in a grid.
StaggeredGridLayoutManager displays the items in the Staggered grid.
Adapter RecyclerView includes a new type of adapter. This is a similar approach to the one already used, but with a few quirks, such as the required ViewHolder.