# Global Music Streaming Listener Preferences Analysis

# Project Overview

This project analyzes a global dataset of music streaming listeners to understand patterns and preferences in terms of streaming platforms, genres, artists, and user behaviors. The analysis covers demographic-based insights, streaming habits, and user engagement rates, providing data-driven observations for the global music streaming industry.

# Dataset Description
[Global_Music_Streaming_Listener_Preferences.csv](https://github.com/louayeldin/global-music-streaming-listener-preferences-analysis/blob/main/data/Global_Music_Streaming_Listener_Preferences.csv)

# Key Columns:

user_id: Unique user identifier

age: Age of the listener

country: Listener's country

streaming_platform: Platform used (Spotify, YouTube, Deezer, etc.)

top_genre: User’s favorite music genre

minutes_streamed_per_day: Daily streaming duration

number_of_songs_liked: Number of songs liked by the user

most_played_artist: Most listened-to artist by the user

subscription_type: Free or Premium account

listening_time_slot: Typical time of day the user listens (Morning, Afternoon, Evening)


# Key Analyses Performed

# Data Cleaning and Preprocessing:

Conversion of data types (converting age column to numeric)

Handling missing values

# Exploratory Data Analysis (EDA):

Top 10 countries by listener count

Streaming platform distribution (visualized by pie chart)

Average minutes streamed per day by age group

Most repeated song rate (calculated as minutes streamed per day divided by number of liked songs)

Most played artist overall

# Platform-Based Analysis:

Total and average minutes streamed per platform

Repeat rate analysis per platform


# Visualizations

Bar charts for top countries, and artists

Pie chart for platform distribution

Histograms for song repetition rates


# How to Run This Project

Clone the repository:

Navigate to the project folder and install dependencies:

Open the Jupyter Notebook in the notebooks / directory and run the analysis.


# Key Insights

Certain platforms show higher streaming engagement per user.

Younger age groups tend to spend more minutes per day streaming.

Some artists like Adele and Ed Sheeran dominate globally as the most played.

Repeat rates differ by platform and age group, indicating user loyalty and preference.


# Requirements

pandas

matplotlib

numpy
