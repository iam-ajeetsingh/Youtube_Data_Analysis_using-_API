# YouTube Data Extraction and Analysis using Youtube API

This project focuses on extracting and analyzing data from YouTube using the YouTube Data API. The goal is to programmatically retrieve video-related data, perform analysis, and generate insights about video attributes such as views, likes, and comments.

## Project Overview

The project involves:
- Connecting to the YouTube Data API using Python.
- Extracting video data based on the search query for "avatar movie"
- Analyzing the extracted data of top 50 videos related to search query to generate insights.
- Exporting the data to CSV file for further use.

## Problem Statement

Videos are a rapidly growing medium for communication, knowledge sharing, and entertainment. YouTube, as one of the largest video platforms, hosts content from diverse professions, cultures, and arts worldwide. Users interact with videos through likes, dislikes, and comments, which reflect their sentiments and engagement.

This project aims to:
- Extract data from YouTube programmatically.
- Analyze video attributes such as views, likes, and comments.
- Provide insights into video performance and user engagement.

## Steps Performed

1. **Connect to the YouTube API**:
   - Created a YouTube API key.
   - Installed the Google API Python client.
   - Established a connection to the YouTube Data API.

2. **Search and Extract Data**:
   - Queried YouTube for videos related to the search term "avatar movie."
   - Extracted video attributes such as:
     - Video ID
     - Channel ID
     - Video Title
     - Channel Title
     - Video Description
   - Retrieved statistics for the top 50 videos, including:
     - Number of views
     - Number of likes
     - Number of comments
   - Exported the data to a CSV file.

3. **Analyze the Data**:
   - Sorted the videos by the number of comments to identify the top 10 most commented videos.
   - Generated insights about video performance and user engagement.


## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Google API Client for interacting with the YouTube Data API.
  - Pandas for data manipulation and analysis.
