# Quickstart

1. Import the project in Eclipse then add it to the build path of your project.
2. Replace your `ListView` with `HeaderListView`
3. Implement a subclass of `SectionAdapter`
4. Set it to your `HeaderListView` with `setAdapter(SectionAdapter adapter)`

# HeaderListView

`HeaderListView` is a list view with sections and with a cool iOS-like "sticky" section headers. Notice that `HeaderListView` is not a subclass of Android's `ListView` but uses composition. Hence, you will need to call `getListView()` to access the underlying `ListView`. 

# Future work

- Handle the case where a section has no header
- Handle the case where the ListView has a header view
- Handle listViews with fast scroll
- Pass ListView XML attributes to the mListView
- See if there are methods to dispatch to mListView