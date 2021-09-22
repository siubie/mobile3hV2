Nama  : Rajendra Rakha Arya P
Kelas : 3H

---

### Summary Minggu Ke-4

## List View

In android development whenever we want to display a scrollable vertical list of items we will use a LisView which has data filled using Adapter

The simplest adapter to use is called an ArrayAdapter because it converts an ArrayList object into a View item that is loaded into a ListView container.

## Custom ArrayAdapter

1. Define the Model
2. Create View Templates
3. Define the Adapter -> ArrayAdapter Inheritance
4. Attaching the Adapter to a ListView
5. Populating Data into ListView


## RecyclerView

RecyclerView is a ViewGroup that renders adapter-based views in a similar way. It should be the successor to ListView and GridView.

Each individual element in the list is defined by the view holder object. You define a view holder by extending RecyclerView.ViewHolder.
The RecyclerView requests the view, and binds the view to its data, by calling a method in the adapter. You define an adapter by extending RecyclerView.Adapter.

The layout manager organizes the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. The layout managers are all based on the library's LayoutManager abstract class.

**RecyclerView provides this built-in layout manager:**

- LinearLayoutManager displays items in a vertical or horizontal scrolling list.
- GridLayoutManager displays items in a grid.
- StaggeredGridLayoutManager displays items in a staggered grid.