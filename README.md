# TheMovieDBApp
Before you continue
------
* The App is still under development so this may contain some errors.<br>
* Generate your own TheMovieDb api [key](https://developers.themoviedb.org/3/getting-started/introduction) <br>
* Create a class named **API_KEY.kt** in **app\src\main\java\kashish\com**
* Copy and paste following code with your API KEY :
  ```kotlin
  class API_KEY{
    companion object {
        val TMDB_API_KEY = "YOUR API KEY";
    }
  }
  ```
 * Create a new firebase [project](https://console.firebase.google.com) and then paste the generated **google-services.json** key in app directory
 * These are required steps, app won't build without these. 
 * Firebase is needed for crashlytics support. 
 * If you don't want to add firebase, just remove all firebase dependencies from gradle file.


Description
---------
* TheMovieDBApp is movies app built with android architecture components and the repository pattern (LiveData, ViewModel, Room, Paging).<br>
* TheMovieDb API is used to fetch movie details.

TO-DO's
---------
* Code clean up.
* Improve UI/UX.

Screenshots
-----------
* **Fragments**<br>
<p float="left">
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/nowshowing.jpg" alt="NowShowing" width="250dp" height="400dp">          
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/upcoming.jpg" alt="Upcoming" width="250dp" height="400dp">         
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/toprated.jpg" alt="TopRated" width="250dp" height="400dp">          
</p>

* **Details Activity**<br>
<p float="left">
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/details1.jpg" alt="Details" width="250dp" height="400dp">          
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/details2.jpg" alt="Details" width="250dp" height="400dp">      
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/details3.jpg" alt="Details" width="250dp" height="400dp">          
</p>

* **Night mode**<br>
<p float="left">
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/nowshowing_dark.jpg" alt="nowshowing_dark" width="250dp" height="400dp">          
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/details1_dark.jpg" alt="Details" width="250dp" height="400dp">      
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/details2_dark.jpg" alt="Details" width="250dp" height="400dp">          
</p>

* **Others**<br>
<p float="left">
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/favourites.jpg" alt="Favourites" width="250dp" height="400dp">          
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/similar.jpg" alt="Similar" width="250dp" height="400dp">      
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/search.jpg" alt="Search" width="250dp" height="400dp"><br>
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/settings.jpg" alt="Settings" width="250dp" height="400dp">
<img src="https://github.com/Kashish-Sharma/TheMovieDBApp/blob/master/Screenshots/chooseregion.jpg" alt="Region" width="250dp" height="400dp"><br>
</p>
