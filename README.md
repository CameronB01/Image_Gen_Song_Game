# Guess the Song from the Image

## Overview

This project transforms your Spotify playlists into a fun guessing game by visualizing song titles using AI-generated images. It consists of three main parts:

    get_songs.ipynb: Extracts song titles from a given Spotify playlist link.
    image_gen.ipynb: Generates images based on the song titles using DALL-E, picking a random song from the provided list.
    open_image.ipynb: Displays the latest generated image, simplifying the process of viewing the AI's creation.

The game's goal is to guess which song title the generated image represents, offering a unique way to interact with your favorite music.

## How to Use
Step 1: Extract Song Titles

    Open get_songs.ipynb in Jupyter Notebook.
    Follow the instructions within the notebook to input your Spotify playlist link.
    After execution, copy the printed list of song titles.

Step 2: Generate an Image

    Open image_gen.ipynb.
    Paste the list of song titles into the track_names list within the notebook.
    Execute the notebook to generate an image based on a random song title from the list.
    Set up a Jupyter Schedule to run however many times a day you'd like.
    Try to guess the song based on the generated image!

Step 3: View the Image

    Open open_image.ipynb to display the latest generated image on your screen.
    No need to manually open the file; this notebook does it for you.
