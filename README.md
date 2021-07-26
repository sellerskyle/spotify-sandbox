
<h1>Spotify Sandbox</h1>

<h2>Introduction</h2>
This repository is a collection of functions I created for interfacing with Spotify's API. This was one of my summer 2020 projects, created to learn about APIs and data science, as well as improve my python competency (with the help of jupyter notebooks).

<h2>Table of Contents</h2>

- Spotify Data Playground
- Spotify User Playground
- Get User Data
- Spotify Test Lab

<h2>Spotify Data Playground</h2>
My first attempt at accessing the Spotify API and playing with some data. Contains basic data manipulation and visualization, like those shown below.



Distribution of song attributes for Global Top 50 Tracks:

![Dist](https://github.com/sellerskyle/spotify-sandbox/blob/main/SpotifyDataPlayground/Screenshots/Dist.PNG)

Correlation between these song attributes for Global Top 50 Tracks:

![Corr](https://github.com/sellerskyle/spotify-sandbox/blob/main/SpotifyDataPlayground/Screenshots/Corr.PNG)

<h2>Spotify User Playground</h2>
Accessing user data has a different authentication flow than requesting generic data, and that's what this notebook dives into. Main functions are to pull your most listened to tracks and artists and save that to a .json file to be used elsewhere. Using this data, it also shows your top genres.

![Weight](https://github.com/sellerskyle/spotify-sandbox/blob/main/SpotifyUserPlayground/Screenshots/Weight.PNG)

<h2>Get User Data</h2>
Compiles and simplifies function to get user's top artists and tracks from Spotify User Playground

<h2>Spotify Test Lab</h2>
A true mixed bag of functions utilizing the Spotify API and data visualization. The most important sections of this notebook are its playback manipulation functions and it's single user constellation to show a user how their top artists are related. This constellation is extended in TwoUserConstellation

![OneUserConstellation](https://github.com/sellerskyle/spotify-sandbox/blob/main/SpotifyTestLab/Screenshots/OneUserConstellation.PNG)
