README for MAVRCK Instagram Scraper:

This Instagram scraper will provide the user with the following metrics:
user, post_link, image_link, post_date, likes, media_type, caption, comments, location, is_ad

By running the scraper provided in the Jupyter notebook file, you will be provided a dataframe containing the previously 
mentioned metrics for the 25 most recent posts for all 96 influencers that have been provided in the initial sample data that MAVRCK provided.

The images are not stored, rather they can be referenced by the links provided in the "image_link" column. The only thing in this link is the raw picture of the instagram post. 
If there are multiple pictures within the post, it will only scrape the first one, and if it is a video it will only scrape the first frame of the video.

The only part of this scraper that you have to do on your own is with getting the igramscraper Python library imported into your Python environment.

The library source code referenced is located here: https://github.com/realsirjoe/instagram-scraper

Because the source code is relatively old and not maintained, I was not able to install the library with a simple "pip install igramscraper" command in my Anaconda command line. 
Instead I had to use the alternative method listed by the creator, utilizing a clone of the github project and installing via the requirements text file. 

In this Github repo I have included this clone, so all you need to do to install this library is to download my files and adjust this filepath 
"C:\MAVRCK-Group-3-Instagram\igscrape\instagram-scraper-master\requirements.txt" so that it corresponds to the filepath on your computer.

In your Anaconda Command Line, enter the following line:
pip install -r "[WHATEVER YOUR FILEPATH IS]\MAVRCK-Group-3-Instagram\igscrape\instagram-scraper-master\requirements.txt"

This should be all you need to install the library onto your machine.

If you just want to use the data that I have already scraped from this, feel free to use the file "scraped_insta_data.csv" instead.

Enjoy!

~Group 3