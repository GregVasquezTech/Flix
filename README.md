# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories


#### REQUIRED (10pts)
- [x ] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x ] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x ] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

![](https://i.imgur.com/0hNmg6l.gif)


### Notes
Describe any challenges encountered while building the app.

I had to take a longer time working with the movie poster because I downloaded the latest version of AlamofireImage. Xcode didn't give a shortcut to writing cell.posterView.af_selfImage(...), but I wrote it manually and xcode was able to understand it. 

Auto layout was also a bit challenging because I had to add constraints for two labels. It would sometimes overlap with each other and that produced an error. After playing around with it, I was able to understand how to give proper constraints for each label.
