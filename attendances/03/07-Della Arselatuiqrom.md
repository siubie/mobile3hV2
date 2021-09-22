Summary Week 3 about Widget Navigation :
-	Widget is main component to build UI in Android
-	UI Hierachy for an Android app is built as a hierarchy of layouts and widgets. You need to define id in XML to manipulate Widget  using Java or Kotlin
-	Navigation Graph :
1.	Destinations are the different content areas in your app
2.	Actions are logical connections between your destinations that represent paths that users can take
-	Navigation Editor :
1.	Destinations panel: Lists your navigation host and all destinations currently in the Graph Editor.
2.	Graph Editor: Contains a visual representation of your navigation graph. You can switch between Design view and the underlying XML representation in the Text view.
3.	Attributes: Shows attributes for the currently-selected item in the navigation graph.

Summary Week 4 about List View and Recycler View :
-	List View in Android development, any time we want to show a vertical list of scrollable items we will use a ListView which has data populated using an Adapter
-	List View Illustration Process :
1. Data Source :
- Cursor
- Arraylist
2. Adapter
3. Adapter View :
- List View
- Grid View
- Spinner
The process illustration from number 1 until number 3.
-	Recyler View a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView. Each individual element in the list is defined by a view holder object. You define the view holder by extending RecyclerView.ViewHolder.
-	The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter.
-	The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class.
-	Recyler View Illustration Process :
-	RecyclerView provides these built-in layout managers :
•	LinearLayoutManager shows items in a vertical or horizontal scrolling list.
•	GridLayoutManager shows items in a grid.
•	StaggeredGridLayoutManager shows items in a staggered grid.
-	RecyclerView includes a new kind of adapter. It’s a similar approach to the ones you already used, but with some peculiarities, such as a required ViewHolder.




