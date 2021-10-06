Summary Week 4 :

ListView 
is Android development, any time we want to show a vertical list of scrollable items we will use a LisView which has data populated using an Adapter. The simplest adapter to use is called an ArrayAdapter because the adapter converts an ArrayList of objects into View items loaded into the ListView container.

RecyclerView 
is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView. Each individual element in the list is defined by a view holder object. You define the view holder by extending RecyclerView.ViewHolder. The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter. The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class.





