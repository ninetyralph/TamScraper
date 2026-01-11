# Tam Scraper
A RetroPie/Emuelec/Batocera/ES-DE compatible gamelist.xml generator using metadata and images from the LaunchBox Games Database.

Tam - To redo/rework แบบไทย

https://ko-fi.com/rogket

![showcase](images/showcase.webp)

I've been there, you wanna scrape all your games but the many collectionists around the world keep the main sources to do it busy or they simply don't have all the info you want.

Well, with Tam it's really easy to customize, and you only focus on what you can see.

Tam uses media from https://gamesdb.launchbox-app.com/.

## Requirements
1. [Python](https://www.python.org/downloads/)
2. Pillow  
Just run "pip install Pillow" from a Command Prompt when you have Python.

## How to Use
1. Install [LaunchBox](https://www.launchbox-app.com/).  
You'll be prompted about which media to download, select Clear Logo, Front and Screenshot.

2. Copy downloaded files into your ROM systems folders.  
Clear Logo, Front and Screenshot folders from C:\Users\yourname\LaunchBox\Images\system\  
Metadata XML from C:\Users\yourname\LaunchBox\Data\system\

3. Run Tam!  
Put TamScraper.py in the root folder where all your system are (EEROMS).  
Open a Command Prompt on it (Type CMD on the Address Bar).  
Run "python TamScraper.py".
