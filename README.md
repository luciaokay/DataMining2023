# Music Recommendation with Spotipy

![image_processing20210706-2486-1m3tb3g](https://github.com/luciaokay/DataMining2023/assets/151770842/792e0b56-f6e8-41d3-9486-75b0a781e883) 

## Overview
This project centers around music recommendation utilizing Spotipy, a Python library for the Spotify API. It offers a seamless experience for users to discover new music based on their preferences.

When working on this project, we recommend using Google Colab for different reasons. 
However, if your workflow is more comfortable with Visual Studio Code, you can still adapt the provided code to your preferred environment.

## Running the Project on Colab
When running the project on Google Colab, ensure you have a folder containing the following files:

• data.zip (to be unzipped for the uploading in the Colab environment) or data.csv (If you prefer, you can download the csv from Google Drive [here](https://drive.google.com/drive/folders/1D2pCa-uhnMvLbTpLH2Rx-9ZaG6lVtVgP?usp=sharing). Once downloaded, you can upload it to your Colab environment)

• data_by_genres.csv

• data_by_year.csv

Upload this folder to your Colab environment before executing the notebook. In the code, we called the folder 'Spotify_Dataset'. 
This data is essential for the music recommendation system to function correctly.


## Requirements

• _Python Libraries_:

spotipy; 
numpy; 
pandas; 
seaborn; 
plotly.express; 
matplotlib.pyplot; 

• _only specific functions from_:

sklearn.cluster; 
sklearn.preprocessing; 
sklearn.pipeline; 
sklearn.manifold; 
sklearn.decomposition; 
sklearn.metrics; 
scipy.spatial.distance; 

• _Credentials_:

Client ID and secret key for Spotify API Access

## Features


valence: Measure of musical positivity, with higher values ​​indicating happier or more positive music.

year: The year the track was released or recorded.

acousticness: Measurement of how acoustic a track is.

artists: List of artists involved in the track.

danceability: Measurement of how suitable a track is for dancing, based on various factors such as tempo, rhythm stability, beat strength and general regularity.

duration_ms: Track duration in milliseconds.

energy: Measurement of intensity. Generally, energetic tracks are fast and loud.

explicit: Indicates whether the track has explicit lyrics (0 = no, 1 = yes).

id: Unique identifier of the track.

instrumentalness: Measures the presence of vocal parts. Higher values ​​indicate fewer voices (more instrumental).

key: The musical key of the track.

liveness: Detects the presence of an audience in the recording. Higher values ​​indicate a greater likelihood that the track was recorded live.

loudness: The overall volume level of the track in decibels.

mode: Musical mode of the track (Major = 1, Minor = 0).

name: The title of the track.

popularity: Measurement of the popularity of the track.

release_date: Release date of the track.

speechiness: Detects the presence of spoken words. Higher values ​​indicate a greater presence of spoken words.

tempo: The tempo of the track in beats per minute (BPM).

Find them [here]([https://drive.google.com/drive/folders/1D2pCa-uhnMvLbTpLH2Rx-9ZaG6lVtVgP?usp=sharing](https://developer.spotify.com/documentation/web-api/reference/get-audio-features))!


## Setting Up Spotify API Access
Spotipy is a Python client for the Spotify Web API, facilitating data fetching and catalog querying. 
Follow these steps to set up your Spotify API access:

• Create a [Spotify Developer](https://developer.spotify.com/)'s account and log in. 

• Navigate to the Spotify Developer Dashboard.

• Click on "Create an App" and fill in the required information to register your app.

After creating the app, you will be provided with a Client ID and secret key. Save these as they will be needed to authenticate your Spotipy requests.

By following these steps, you ensure that your Spotipy library is correctly set up and authenticated to access the Spotify API for seamless music recommendation.

In the Music_Recommendation.ipynb file, Spotify credentials have been pre-inserted with some example credentials that are functional for demonstration purposes. Feel free to replace them with your own credentials for actual usage.

## Next Steps:

• Curating the UX and eventually UI by integrating the classificator to the Spotify Player and Application 

• Expanding the data.cvs to access broader possibilities in the generation of the output
