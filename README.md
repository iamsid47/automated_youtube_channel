# Fully Automated Youtube Channel

Code to run a fully automated youtube that can scrape content, edit a compilation, and upload to youtube daily.

# Instructions

1. [Download](https://github.com/nathan-149/automated_youtube_channel/archive/main.zip) the Github Repository

2. Download and install [Python](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/)

3. Run `pip install -r requirements.txt`

4. Get setup and create a Project with the Youtube API: https://developers.google.com/youtube/v3/quickstart/python
Be sure to follow it carefully, as it won't work if you don't do this part right.
Download your OATH file as "secret.json" in your folder.

5. Run `python3 setup_google.py` and follow the web page that opens up.

6. Create an instagram account and follow accounts you want to scrape from

7. Open main.py in a text editor and fill in necessary information

8. Run `python3 main.py`

9. Enjoy your fully automated youtube channel! :) Note that for uploading public videos, you have to complete an audit for the Youtube API. See the note in the [Google Documentation](https://developers.google.com/youtube/v3/docs/videos/insert)
