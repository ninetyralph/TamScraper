# Tam Scraper
![showcase](images/showcase.webp)

A RetroPie/Emuelec/Batocera/ES-DE compatible gamelist.xml generator using metadata and images from the LaunchBox Games Database.

Tam - To redo/rework แบบไทย

I've been there, you wanna scrape all your games but the many collectionists around the world keep the main sources to do it either busy or they simply don't have all the info you want.

Tam it's really easy to customize, and you only focus on what you can see.

https://gamesdb.launchbox-app.com/

## Features
1. LaunchBox Integration  
Tam uses the huge LaunchBox Games Database which doesn't struggle with a couple requests.
2. Optimization  
Media gets adjusted automatically ensuring it doesn't get stretched or lag the UI.
3. Lightweight  
It's a tiny script, you can run and forget it.

## Requirements
1. [Python](https://www.python.org/downloads/)
2. Pillow  
Run "pip install Pillow" on a Command Prompt after installing Python.

## Download
You can use it anywhere that supports Python, including Windows.  
[Download](https://github.com/ninetyralph/TamScraper/releases/download/release/TamScraper.py)

## How to Use
1. Install [LaunchBox](https://www.launchbox-app.com/).  
You'll be prompted about which media to download, select Clear Logo, Front and Screenshot.

2. Copy downloaded files into your ROMs system folders.  
Clear Logo, Front and Screenshot folders from C:\Users\yourname\LaunchBox\Images\system\  
Metadata XML from C:\Users\yourname\LaunchBox\Data\system\

3. Run Tam!  
Put TamScraper.py in the root folder of all your ROMs (EEROMS).  
Open a Command Prompt on it (Typing CMD on the Address Bar).  
Run "python TamScraper.py".

## About

Tam links your media by default to commonly used tags by Recalbox themes.  
1. Clear Logos -> Marquees
2. Boxart -> Covers
3. Screenshots -> Fanarts

If you would like to change any you can easily do so by opening the gamelist file with a text editor, selecting and replacing all tags.

If you like the project and would like to donate, you can do so here:  
https://ko-fi.com/rogket
