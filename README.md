# Spotify Playlist  Analysis  

In this project, I analyzed my personal Spotify playlists and trained an SVM as a song recommender. 
For the analysis, I used Spotipy which is a Python library for the Spotify Web API. Spotipy offers 
access to the music on Spotify and audio features of the songs.



## How can you use it?

### Technical Requirements

- Python 3.6 
- Pandas
- scikit-learn
- scikit-optimize
- spotipy


### Spotify Requirements

- Spotify account and >= 1 playlist
- create an app on [Spotify Dashboard](https://developer.spotify.com/dashboard/) $\rightarrow$ get client id and client secret


### Files

The important files are:
* train_spotify_music.ipynb: 
    - calculate mean and variance of audio features
    - compare BPMs of playlists
    - train SVM model as song recommender
* predict_spotify_model.ipynb: 
    - predict if a song would fit into the playlist using the SVM model
