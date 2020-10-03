# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

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
