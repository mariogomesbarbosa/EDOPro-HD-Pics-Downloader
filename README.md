# YGO Pics Downloader

![Program version](https://img.shields.io/badge/Version-2.3.1-blueviolet?style=flat-square)
![Python version](https://img.shields.io/badge/Python-3.10-blue?style=flat-square)
![Pygame version](https://img.shields.io/badge/Pygame-2.1-green?style=flat-square)

This is a modification of the [EDOPro HD Pics Downloader](https://github.com/AlexsanderRST/EDOPro-HD-Pics-Downloader) project with the aim of including the option to download, in addition to the card images, the art images as well. All program development rights are assigned to [Alexander Rosante](https://github.com/AlexsanderRST)

This program automates the process of:
- Access [YGO Cards Database](https://db.ygoprodeck.com/); 
- Choose a card;
- Scroll down to 'Download JPG image' or 'Download Cropped Art Image' option;
- Download it into pics folder.

# How it works?

- Put yours deck files '.ydk' on the 'deck' folder;
- Open the 'YGO-Pic-Downloader.exe' (~10 MB);
    - Or 'YGO-Pic-Downloader.py' (~20 kb) (⚠️[Python 3.10+](https://www.python.org/) and [Pygame 2.0+](https://pypi.org/project/pygame/) required);
- Type the name of the '.ydk' file you want to download;
- Click on 'Cards' to download the entire card image;
- Click on 'Artworks' to download the cropped art image.

The method is simple, a python script gets a list of cards ids in a ydk file and use link manipulation to download card per card directly into the pics folder.

## Tips:
- **The program does NOT update automatically**. Update it may solve some issues;
- The ydks in this repo update automatically. Download the ydks every time it is updated is not necessary;
- When downloading all cards, apparently, the download goes faster if all cards pics were deleted before;
- If the allcards.ydk is not deleted after the download (Use the 'Delete ydk' button): the game may open it at deck edit and severe lagging will occour.

## Now with an Interface! 
![interface img](https://mario-design.s3.us-east-2.amazonaws.com/YGO-Pic-Downloader-1.png)

## Features:
- **Download all cards pics**. It may take a while since is over 9000 cards;
- **Download all fields artworks**;
- **Download all new cards**. New cards added to *allcards.ydk* since the last update;
- **Download deck's cards pics**. Downloads card pics from a deck name (Text Box).
- **Download deck's cards arts**. Downloads card arts pics from a deck name (Text Box).

## Compatibility:
#### 👍:
- Windows 10, 11;
- All released TCG/OCG cards;
- All tokens;
- Some pre-released (beta) TCG/OCG cards;
- Some Rush cards.
#### 👎:
- Windows 7 or lower;
- Anime/Unofficial/Custom cards.
