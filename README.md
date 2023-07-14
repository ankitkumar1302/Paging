<h1>Paging 3 with Compose Demo</h1>

<!-- Existing overview section -->

<h2>Key Implementations</h2>

<ul>
  <li>Dagger Hilt - For dependency injection</li>
  <li>Kotlin KAPT - For annotation processing</li>
  <li>Kotlin Serialization - For parsing JSON</li>  
  <li>Paging 3 - For gradual data loading</li>
  <li>Jetpack Compose - For building UI</li>
</ul>

<!-- Running app section -->

<h2>Building the Project</h2>

<p>To build the app:</p>

<ol>
  <li>Enable kapt plugin in Gradle</li>
  <li>Add KotlinX Serialization dependencies</li>
  <li>Sync and compile using Dagger Hilt KAPT</li>
</ol>

<h2>Running the app</h2>

<p>The app uses the Unsplash API to load images.</p> 

<ol>
  <li>Get an API key from <a href="https://unsplash.com/developers">Unsplash Developers</a></li>
  
  <li>Add the key to local.properties</li>
  
  <li>Sync gradle</li>
  
  <li>Run the app on emulator or device</li>
</ol>

<p>The app will now load paginated images from Unsplash using your API key!</p>

<p>Then run the app on a device or emulator as usual.</p>
