#### Youttube Data extraction :Project Overview

This repository is about extracting data from YouTube using the developer API. The goal is to analyze the #endsars# trend that rocked the entire world.

## Task
Script that extracts YouTube data to analyze the #endsars# trend.
The script answers the following:
*	Filter out channels and playlists.
*	Get only videos published this year.
*	Include videos that are between 4 to 20 mins long.
*	Generic such that the search query can be changed.
*   Output should have filename : current_timestamp_youtube_data


The following video should contain the following attributes:
*	the time video was published
*   the video id
*	the title of the video
*	description
*	the URL of the video thumbnail
*	number of views
*	number of likes
*	number of dislikes
*	number of comments
*   A the column that builds the video URL using the video id

## Code and resources used
...**Python version** : 3.6
...**Packages** : json, pandas
...**Web Framework**: virtual environment, requirements.txt
...Articles that help complete the script
* [Get started here](https://developers.google.com/youtube/v3/getting-started)
* [Get the API key](https://rapidapi.com/blog/how-to-get-youtube-api-key)
* [video tutorial from Coursera](https://www.coursera.org/lecture/social-media-data-analytics/video-4-using-python-to-extract-data-from-youtube-hfelS)
* [YouTube API documentations](https://youtube-data-api.readthedocs.io/en/latest/youtube_api.html)

## Activities done
1. Idealy the first step was to create a credential authorization credentials. What's needed is a google (gmail) account
2. Set-up your environment. There're a number of environments data engineers can deploy for this exercise. E.g, google colab, jupyter notebook, etc.
3. Install the necessary packages and updates (*if necessary*): apiclient, oauth2client
4. Install packages for the virtual environment

    
