## Interactive Spotify Data Analysis Tool

🎵 Overview

This project is an interactive data analysis tool designed for exploring Spotify data using visual analytics. Built with Shiny in R, this application enables users to investigate musical trends, genre popularity, and key audio characteristics of songs. The tool is particularly useful for music producers and analysts seeking insights into what makes a song popular.

📌 Features

Interactive heatmaps to analyze loudness across different sections of a song.

Streamgraphs to visualize how genre popularity has evolved over time.

Parallel coordinate plots to compare different genres based on key audio features.

Bubble plots to study the relationship between energy, beats per minute (BPM), and song popularity.

User-friendly web interface built using Shiny.

Data sourced from the Spotify API, including the Billboard TikTok Top 50 songs for analysis.

📂 Repository Structure

📂 Spotify_Data_Visualization
├── 📁 data                  # Datasets extracted from Spotify API
├── 📁 scripts               # Data processing and analysis scripts
├── 📁 shiny_app             # R Shiny application files
├── 📁 results               # Output data and generated visualizations
├── app.R                    # Main application script for Shiny
├── requirements.R           # Dependencies required for execution
├── README.md                # Project documentation

📊 Data Sources

The project utilizes Spotify API data, analyzing various song attributes such as:

Loudness: Variation of volume within different parts of a song.

Genre Popularity: Evolution of musical genres over time.

Audio Features: Energy, danceability, instrumentalness, speechiness, and more.

BPM & Popularity: Examining how tempo influences a song’s success.

🚀 Getting Started

1️⃣ Install Required Packages

Ensure you have R and RStudio installed. Then, install the required dependencies:

install.packages(c("shiny", "shinyWidgets", "ggplot2", "dplyr", "bslib", "shinyBS", "GGally", "viridis"))

2️⃣ Run the Application

Set your working directory to the project folder and execute:

library(shiny)
runApp("shiny_app")

This will launch the web application in your browser.

📺 Application in Action

The Shiny app is also deployed online! You can access it here:
Live App Deployment

🛠 Implementation Details

Language & Framework: Developed in R using Shiny.

Visualizations:

ggplot2: Used for custom plots.

GGally: Generates parallel coordinate plots.

Interactivity: Users can filter and customize their analysis dynamically.

📌 Key Insights

Loudness Analysis: Heatmaps provide insights into song structure without listening to the audio.

Genre Popularity: Temporal trends in music genres are displayed via streamgraphs.

Audio Features Comparison: Parallel coordinates allow simultaneous analysis of multiple song attributes.

Song Popularity Drivers: Bubble plots uncover the correlation between energy, BPM, and success.
