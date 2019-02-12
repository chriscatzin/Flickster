## Christopher Catzin
## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [x] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [x] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF
https://github.com/chriscatzin/Flickster/blob/ff9e2b607e5637b88bb4507a5bf3a4a62d8b3019/Flickster-Part%20Two.gif

<img src="https://github.com/chriscatzin/Flickster/blob/ff9e2b607e5637b88bb4507a5bf3a4a62d8b3019/Flickster-Part%20Two.gif" width=250><br>

### Notes

Describe any challenges encountered while building the app.

Some challenges I encountered while working on the second part of this app was importing the YouTube
Android Player into Android Studio. I was getting errors when I was declaring YouTubePlayerView youTubePlayerView.
For some reason Android Studio did not want to import the library, but turns out I was importing the entire file
instead of the .jar file within that file after extracting the zip file. Another problem I ran into was improving
view lookups using @BindView instead of findViewById for Activity View Lookups. I was getting errors, but I forgot to 
add the dependencies to the app/build.gradle. The Last challenge that I had was Improving Listener Attachments, and 
Improving Resource Lookups. I did not finish, but I hope to go back and finish the rest of the bonus section sometime 
this week. Overall, this was a really fun project, and I learned so much material.


## Open-source libraries used
- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android



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
