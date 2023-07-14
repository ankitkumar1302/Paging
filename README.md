# Paging
Paging 3 Demo
This project demonstrates how to implement pagination in an Android app using Jetpack Paging 3.

Overview
The app shows a simple list of data loaded from a backend API using Paging 3 to enable gradual loading rather than loading all data upfront.
The UI is implemented using Jetpack Compose, with a LazyColumn for showing the paged list data.

Key implementations:

LazyColumn - For displaying the paged list
PagingDataAdapter - For binding paged data to LazyColumn
PagingSource - For loading pages of data from network
ViewModels - To stream PagingData to Compose UI
Running the app
The app is built using Compose for the UI. To run:

Get API key
Sync gradle
Run on device or emulator
Scroll down to load more pages thanks to Paging 3 and Compose!
