# [EDOPro/Ygopro](https://discord.gg/ygopro-percy) HD Pics Downloader 2.1.4

This program automates the process of:
- Access [YGO Cards Database](https://db.ygoprodeck.com/); 
- Choose a card;
- Scroll down to 'Download JPG image' option;
- Download it into the game's pics folder.

The method is simple, a python script gets a list of cards ids in a ydk file and use link manipulation to download card per card directly into the pics folder.

![card comparison](https://i.ibb.co/Y49skyJ/card-comparison.png)

The size of game default card pic is 177x254 and the pics downloaded by this program is 421x614 (139% larger and 142% taller). 

## Instalation:
- Download [exe](https://github.com/AlexsanderRST/edopro-hq-pics-downloader/blob/30799522aaee38cc0c15436482f4f876b8fc15f9/HQ%20Pics%20Downloader.exe) (~10 MB) 
- **or** [py](https://github.com/AlexsanderRST/edopro-hq-pics-downloader/blob/30799522aaee38cc0c15436482f4f876b8fc15f9/HQ%20Pics%20Downloader.py) (~15 kb) (⚠️[Python 3](https://www.python.org/) and [Pygame 2](https://pypi.org/project/pygame/) required);
- Copy the file into your game folder;
- Double-click exe or py file.

## Update tips:
- **The program does NOT update automatically**. The substitution of the your version to the newer may solve some crashes (If it still having crashes, open an Issue);
- The ydks in this repo update automatically. You don't need to download them every time an update is launched.

## Now with an Interface! 
![interface img](https://i.ibb.co/gvGvqhb/hdpd-214.png)

## Features:
- **Download all cards pics**. It may take a while since is over 9000 cards;
- **Download all fields artworks**;
- **Download all new cards**. New cards added to *allcards.ydk* since the last update;
- **Download deck's cards pics**. Downloads card pics from a deck name (Text Box).

## Extras:
- The card names usually change from OCG to TCG. There is no function in the program specifically for new TCG cards, but the *New TCG.ydk* in the repository covers these releases.

## Compatibility:
#### 👍:
- Windows 10, 11;
- All released TCG/OCG cards;
- Some pre-released (beta) TCG/OCG cards;
- Some Rush cards.
#### 👎:
- Windows 7 or lower;
- Anime/Unofficial/Custom cards.

## You can help me:
- Open an Issue if you have problems;
- Or donate: [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=L53Z8HUNP7X66)
