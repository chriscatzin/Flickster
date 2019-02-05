## Christopher Catzin
## Flix Part 1


#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [x] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.com/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x] (2pts) Improved the user interface by experimenting with styling and coloring.
- [x] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF
https://github.com/chriscatzin/Flickster/blob/master/Flickster.gif

<img src="https://github.com/chriscatzin/Flickster/blob/master/Flickster.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.

Some challenges that I ran into were minor, like adding a space where there wasn't suppose to be a space or a missing semicolon. 
Also I had trouble trying to get the landscape view correctly, but eventually I found out I had to make some changes to the text
view in layout-land. Overall, this was a fun project!

### Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
