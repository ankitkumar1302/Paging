<h1>Paging 3 with Compose Demo</h1>

<h2>Overview</h2>

<p>The app shows a scrollable list of data loaded from a backend API using Paging 3 for gradual loading.</p>

<p>The UI is implemented using Jetpack Compose, with a LazyColumn for showing the paged list data.</p>

<p>Key implementations:</p>

<ul>
  <li>LazyColumn - For displaying the paged list</li>  
  <li>PagingDataAdapter - For binding paged data to LazyColumn</li>
  <li>PagingSource - For loading pages of data from network</li>
  <li>ViewModels - To stream PagingData to Compose UI</li>
</ul>

<h2>Running the app</h2>

<p>The app is built using Compose for the UI. To run:</p>

<ol>
  <li>Get API key</li>

<h2>Running the app</h2>

<p>The app uses the Unsplash API to load images.</p> 

<ol>
  <li>Get an API key from <a href="https://unsplash.com/developers">Unsplash Developers</a></li>
  
  <li>Add the key to local.properties</li>
  
  <li>Sync gradle</li>
  
  <li>Run the app on emulator or device</li>
</ol>

<p>The app will now load paginated images from Unsplash using your API key!</p>
  
  <li>Sync gradle</li> 
  <li>Run on device or emulator</li>
</ol>

<p>Scroll down to load more pages thanks to Paging 3 and Compose!</p>
