# YouTube-API
This repository is about pulling data from YouTube using the developer API
The following is the assignment that led to this repo
YouTube Data extraction.

Task:
Write a script that extracts YouTube data to analyze the #endsars# trend that rocked the entire world.
The script should be able to perform the following:
•	Filter out channels and playlists.
•	Get only videos published this year.
•	Include videos that are between 4 to 20 mins long.
•	Generic such that the search query can be changed.

Output:
Store the output into a csv with the filename having the following format: current_timestamp_youtube_data.

The following video attributes should be a part of the dataset:
•	the time video was published
•	the video id
•	the title of the video
•	description
•	the URL of the video thumbnail
•	number of views
•	number of likes
•	number of dislikes
•	number of comments
Create an additional the column that builds the video URL using the video id.
Resources
YouTube API source: https://developers.google.com/youtube/v3/getting-started
