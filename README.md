Spotify Song Recommendation System

This project was developed as part of the Nights and Weekends Season 5, Week 2 task. The objective was to build a toy version of an actual product—a Spotify song recommendation system.

Overview

The Spotify Song Recommendation System is designed to provide users with a list of recommended songs based on a given song URL. The system leverages the Spotify API to fetch song features and uses a custom-trained model to identify and recommend similar songs.

Features

Using your spotify credentials: i have made this version where you have to upload your spotify credentials through which you have to select a playlist of yours so that it can recommend songs based on your music taste.
Datasets used: for this project i have only used a 50 songs playlist created by spotify as my dataset but you can totally use a much larger dataset i.e some of them are "Million Playlist Dataset MPD" or "yama erenay's kaggle dataset"

Song Recommendation: Based on the input song's features, the system generates a list of 40 recommended songs, but in my example it only recommends me 1 song/album which is from mm food... this i because i had only 1 playlist in my spotify which has like 5-6 songs in that it found a similar match i.e mm food... so it only recommended 1 song but this is only for my case because my training and testing data is less because its only a toy version.

Project Structure
The project consists of the following key components:

Data Preparation: Processing and preparing song data for training.
Model Training: Training a recommendation model using the song features.
Recommendation System: Implementing the function to recommend songs based on a given song URL.
Jupyter Notebooks: Includes code and explanations for each step.
