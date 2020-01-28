## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF
<img src='https://imgur.com/CvbNVnY.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Notes

Making the changes for Unit 2 went very smoothly, aside from a few hiccups regarding the emulator. I installed an SSD in place of my hard drive in my laptop over the weekend, which required some reconfiguring and proper pulls from my own git library to continue work on my project. 

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF
<img src='https://github.com/parkerallbritton/Flixster/blob/master/walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Notes
Just like with last week's project, the emulation of a virtual android device is unreliable at best and crashes/fails to load ot begin with on my current computer. Following the guide for using my personal Android device instead to run the app and make a video walkthrough on it proved just as innefective. I am constantly working to resolve this issue, but I have yet to emulate the app.
I was able to succesfully boot the virtual device a single time. However, the Flix app was not loaded onto the device. Attempting to restart the virtual device merely put me back at square one: unable to boot the virtual Pixel phone.

*UPDATE*
I was able to properly load the emulator, after much deliberation and the use of every remaining ounce of patience in my body, and record a gif of the user stories to push to the repository and the readme.  
### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
