This project provides a web application for sentiment analysis of YouTube comments. It allows users to input a YouTube link and analyzes the sentiment of the comments associated with that video. The application also displays video information, channel information, and visualizations of the sentiment analysis results.

Features 
Extracts the video ID from a YouTube link.
Retrieves comments from the specified YouTube video and saves them to a CSV file. 
Performs sentiment analysis on the comments using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. 
Generates bar charts and scatter plots to visualize the sentiment analysis results. 
Retrieves video and channel information from the YouTube API. 
Provides an interactive web interface using Streamlit. 
Installation 
Clone the repository:

Install the required dependencies:

Obtain a YouTube Data API key from the Google Cloud Console and replace YOUR_API_KEY in YoutubeCommentScrapper.py with your actual API key.

Run the application:

Usage 
Open the application in your web browser.

Enter a valid YouTube link in the sidebar. 

Wait for the application to retrieve the video and channel information, save the comments to a CSV file, perform sentiment analysis, and display the results. 

Explore the sentiment analysis results, video information, and channel information. 
