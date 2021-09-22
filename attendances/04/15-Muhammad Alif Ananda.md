22/09/2021

#TODAY'S RECORD ( WEEK 4 )

today were learning about list view and recycle view.

the meaning of list view itself is :

list view is an adapter view that does not know the details, such as type and contents, of the views it contains. Instead list view requests views on demand from a ListAdapter as needed, such as to display new views as the user scrolls up or down.

In order to display items in the list, call setAdapter(android.widget.ListAdapter) to associate an adapter with the list. For a simple example, see the discussion of filling an adapter view with text in the Layouts guide.

while the meaning of recycle view is :

RecyclerView is a widget that is more flexible and advanced version of GridView and ListView. It is a container for displaying large datasets which can be scrolled efficiently by maintaining limited number of views. You can use RecyclerView widget when you have data collections whose elements change at runtime depend on network event or user action.

#RecyclerView differs from its predecessor ListView primarily because of the following features:

Required ViewHolder in Adapters - ListView adapters do not require the use of the ViewHolder pattern to improve performance. In contrast, implementing an adapter for RecyclerView requires the use of the ViewHolder pattern for which it uses RecyclerView.Viewholder.

Customizable Item Layouts - ListView can only layout items in a vertical linear arrangement and this cannot be customized. In contrast, the RecyclerView has a RecyclerView.LayoutManager that allows any item layouts including horizontal lists or staggered grids.

Easy Item Animations - ListView contains no special provisions through which one can animate the addition or deletion of items. In contrast, the RecyclerView has the RecyclerView.ItemAnimator class for handling item animations.

Manual Data Source - ListView had adapters for different sources such as ArrayAdapter and CursorAdapter for arrays and database results respectively. In contrast, the RecyclerView.Adapter requires a custom implementation to supply the data to the adapter.

Manual Item Decoration - ListView has the android:divider property for easy dividers between items in the list. In contrast, RecyclerView requires the use of a RecyclerView.ItemDecoration object to setup much more manual divider decorations.