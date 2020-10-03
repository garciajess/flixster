# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flixster Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="flixsterGif2.gif" width=250><br>

### Notes
This update includes similar movies to the recently released movies in the form of a Collection View. When working with the tab bar controller for multiple table views, the story board entry point was in the Now Playing Scence instead of the Tab Bar Controller Scence. This caused the program to maintain a black screen after the launchscreen. After moving the entry point, the app was able to run successfully and display all of the data properly.

---

## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://media.giphy.com/media/uplrl6fqG8LjTZzZKh/giphy.gif" width=250><br>

### Notes
One challenge I encounted while building the app was modifying the synopsis label so that multiple lines were diaplayed for each movie instead of only one line. I tried expanding the label's size, but after doing some research I realized I had to switch the "Lines" in the Attributes inspector to 0. This fixed the issue I was having and allowed for the synposis to be displayed in multiple lines. After this assignment, I feel more comfortable with creating custom cells and creating a network request to get data returned from the API. 
