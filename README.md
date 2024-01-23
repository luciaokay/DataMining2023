# Music Recommendation with Spotipy

![image_processing20210706-2486-1m3tb3g](https://github.com/luciaokay/DataMining2023/assets/151770842/792e0b56-f6e8-41d3-9486-75b0a781e883) 

## Overview
This project centers around music recommendation utilizing Spotipy, a Python library for the Spotify API. It offers a seamless experience for users to discover new music based on their preferences.

When working on this project, we recommend using Google Colab for different reasons. 
However, if your workflow is more comfortable with Visual Studio Code, you can still adapt the provided code to your preferred environment.

## Requirements

• Python Libraries:

spotipy

numpy

pandas

seaborn

plotly.express

matplotlib.pyplot

• Only specific Functions from:

sklearn.cluster; 
sklearn.preprocessing; 
sklearn.pipeline; 
sklearn.manifold; 
sklearn.decomposition; 
sklearn.metrics; 
scipy.spatial.distance; 

• Credentials:

Client ID and secret key for Spotify API Access

## Setting Up Spotify API Access
Spotipy is a Python client for the Spotify Web API, facilitating data fetching and catalog querying. 
Follow these steps to set up your Spotify API access:

• Install Spotipy using the following command:

bash
Copy code
!pip install spotipy

• Create a Spotify Developer's account and log in.

• Navigate to the Spotify Developer Dashboard.

• Click on "Create an App" and fill in the required information to register your app.

After creating the app, you will be provided with a Client ID and secret key. Save these as they will be needed to authenticate your Spotipy requests.

By following these steps, you ensure that your Spotipy library is correctly set up and authenticated to access the Spotify API for seamless music recommendation.

## Running the Project on Colab
When running the project on Google Colab, ensure you have a folder containing the following files:

• data.zip (to be unzipped for the uploading in the Colab environment)

• data_by_genres.csv

• data_by_year.csv

Upload this folder to your Colab environment before executing the notebook. In the code, we called the folder 'Spotify_Dataset'. 
This data is essential for the music recommendation system to function correctly.
