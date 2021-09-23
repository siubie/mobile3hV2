# Widget and Navigation

## Widget
- Main component to build UI in Android
- Inherits from view class
- Example: EditText, ImageView, RadioButton, CheckBox, etc.

## Navigation
- Navigation between different screens and apps is a core part of the user experience. 
- Destination: This is the first screen and last screen the user sees when they launch your app.
- Navigation Graph: Connect between destinations that represent paths that users can take
- Navigation Editor: Can edit the graph

# ListView & RecyclerView

## ListView
- In Android development, any time we want to show a vertical list of scrollable items we will use a LisView which has data populated using an Adapter
- The simplest adapter to use is called an ArrayAdapter because the adapter converts an ArrayList of objects into View items loaded into the ListView container.
- How to custom ArrayAdapter: Define the Model -> Create View Template -> Define the Adapter -> ArrayAdapter Inheritance -> Attaching the Adapter to a ListView -> Populating Data into ListView

## RecyclerView
- RecyclerView is a ViewGroup that renders any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView. 
- First, define the view holder by extending RecyclerView.ViewHolder.
- Then, define the adapter by extending RecyclerView.Adapter.
- You can use one of the layout managers provided by the RecyclerView library, or you can define your own.

## LayoutManagers
RecyclerView provides these built-in layout managers:
- LinearLayoutManager shows items in a vertical or horizontal scrolling list.
- GridLayoutManager shows items in a grid.
- StaggeredGridLayoutManager shows items in a staggered grid.

## Adapter
- RecyclerView includes a new kind of adapter. It’s a similar approach to the ones you already used, but with some peculiarities, such as a required ViewHolder. 
- You need to override three methods: onCreateViewHolder(), onBindViewHolder(), getItemCount()
