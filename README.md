# YouTube Data extraction :Project Overview

This repository is about extracting data from YouTube using the developer API. The goal is to analyze the #endsars# trend that rocked the entire world.

### Task
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

### Code and resources used
**Python version** : 3.6
**Packages** : json, pandas
**OS** :macOS Catalina
**Web Framework**: virtual environment, requirements.txt
Articles that help complete the script
* [Get started here](https://developers.google.com/youtube/v3/getting-started)
* [Get the API key](https://rapidapi.com/blog/how-to-get-youtube-api-key)
* [video tutorial from Coursera](https://www.coursera.org/lecture/social-media-data-analytics/video-4-using-python-to-extract-data-from-youtube-hfelS)
* [YouTube API documentations](https://youtube-data-api.readthedocs.io/en/latest/youtube_api.html)

### Activities done:
1. #### Create Credentials
Idealy the first step was to create a credential and generate authorization. What's needed is a google (gmail) account. [Use this link to create the account](https://developers.google.com/youtube/v3/getting-started). Getting authorization from google is instant not too stressful.

2. #### Set-up your environment.
The kind of environment to use is key. There're a number of environments data engineers can deploy for this exercise. E.g, google colab, jupyter notebook, etc. I used jupyter notebook because I am conversant with it and also becuase all I do is saved on my local computer. For google colab, you'll need internet to create your workspace and to access your files. In situations where you have unstable internet, it delays execution of your project.

3. #### Install the necessary packages 
By defualt, jyputer notebook doesn't come with pre-installed packages for interaction with youtube. I had to install the google apiclient ($ pip install --upgrade google-api-python-client), and the authentication client ($ pip install google-auth). Before installing these libraries, be sure to check your python version to aid installation of the appropriate client version and authentication version.

4. #### define your own module
The next step I took was to hide my credentials by writing a script in my local container. I then imported the module in my script and called the credentials. First, I created a python script called dir having __init__.py and a second script in the same folder as the dir which I named key.py having credentials = {"DEVELOPER_KEY": "xxxxxxxx"} as the only script.

5. #### Define a function for the script
I proceeded to define a function to complete the task.

6. #### Download and save in .py
Working in jupyter notebook stores files in .ipynb but to save as a script, i.e. .py, I downloaded the file as Python(.py)

7. #### Create requirements.txt
I wasn't using any text editor, so my only option was to use Vs Code to access my .py file to create a virtual environment and the requirements.txt. If you're new to using virtual environment, [this material](https://code.visualstudio.com/docs/python/python-tutorial) could be of help if you want to use Vs code.
    
