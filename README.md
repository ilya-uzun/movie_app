
### User Experience

### Your app will:
 * Upon launch, present the user with an grid arrangement of movie posters.    
 * Allow your user to change sort order via a setting:  
    * The sort order can be by most popular, or by top rated     
 * Allow the user to tap on a movie poster and transition to a details screen  with additional information such as:    
    * original title     
    * movie poster image thumbnail     
    * A plot synopsis (called overview in the api)     
    * user rating (called vote_average in the api)    
    * release date    
 
### Requirements:

 * Movies are displayed in the main layout via a grid of their corresponding  movie poster thumbnails.     
 * UI contains an element (i.e a spinner or settings menu) to toggle the sort order of the movies by: most popular, highest rated.     
 * UI contains a screen for displaying the details for a selected movie.     
 * Movie details layout contains title, release date, movie poster, vote      average, and plot synopsis.
 * App utilizes stable release versions of all libraries, Gradle, and Android Studio.     

#### User Interface - Function
 * When a user changes the sort criteria (“most popular and highest rated”) the main view gets updated correctly.
 * When a movie poster thumbnail is selected, the movie details screen is launched.

#### Network API Implementation     
 * In a background thread, app queries the `/movie/popular` or `/movie/top_rated` API for the sort criteria specified in the settings menu.    


