# Mega Link Downloader Bot
<p align="center"><b>This is a telegram bot to download mega.nz links and return them as files/videos - Made by a 100% noob!</b></p>

<p align="center">(When I mean noob I really mean noob!)</p>

<b>You can find a live version of this bot in telegram as [@mega_downloader_robot](https://t.me/mega_downloader_robot)</b>

Created with ❤️ by <b>[@xmysteriousx](https://t.me/xmysteriousx)</b> as a part of [@mysterious_uploader_robot](https://t.me/mysterious_uploader_robot)

<p align="center"><a href="https://t.me/rezoth_tm"><img src="https://img.shields.io/badge/Telegram-Join%20Telegram%20Group-blue.svg?logo=telegram"></a></p>

Please be kind to star and fork this repo!✨😇
<br>

---

## Features 💫
 - Mega accounts are not needed!
 - Parellel download are supported! (This means many users can use the bot at the same time. 😇)
 - No quota limits will be occured!
 - Custom thumbnail support!
 - Custom caption support!
 - Ability to download any file under 2GB and return as a telegram file!
 - Abilty to download upto size of 5GB files! (If you provide a pro/business account when deoloying there will be no file size limits! 😍)
<b>Note</b> :- Due to telegram API limits I can't upload files which are bigger than 2GB so the files will be spliited and uploaded to you!

---

### More features that I can add! (easily) 😍😋
- Feature of uploading telegram-files / direct-links to your mega account!
- A messgae broadcasting system for users!
- Un-wanted users blacklisting system!

---

## Deploying Methods

<details>
  <summary><b>Deploying to Heroku (The Easiest Way)</b></summary>

<br>

- Choose Europe as server location when deploying. (Beacuse downloadings will be fast!).
- Examples of needed bot variables are mentioned below in this readme!

<br>
  
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/XMYSTERlOUSX/mega-link-downloader-bot)
</details>

<details>
  <summary><b>Deploy to your VPS</b></summary>

<br>

**Make a vps (Recommended - Ubuntu 20.04 (LTS) x64 vps from a location/region near to New Zealand) and log in to it.**
- Then execute the below commands. 👇
```sh  
sudo apt update
```
```sh  
sudo apt upgrade
```
```sh  
apt-get update
```
```sh  
apt-get install tmux
```
```sh  
tmux
```
**Now there are two methods to go further!**
- Method 1
  
  - Fork my repo. In the repo go inside to the `sample_config.py` and copy all the code in it. In your forked repo, create a file named `config.py` and paste the whole code in it. 
  - Then edit the values in it with your values! (Inside your `config.py` file you will see the examples of how to edit the fields.)
  - Then execute the below commands. 👇

```sh  
git clone You_forked_repo_url
```
```sh  
apt install python3-pip
```
```sh  
apt install ffmpeg
```
```sh  
cd mega-link-downloader-bot
```
```sh  
pip3 install -r requirements.txt
```
```sh  
python3 bot.py
```
Now If you did everything correctly bot will be running successfully! 🥳

- Method 2

  - Execute the below commands. 👇

```sh  
git clone https://github.com/XMYSTERlOUSX/mega-link-downloader-bot
```
```sh  
apt install python3-pip
```
```sh  
apt install ffmpeg
```
```sh  
cd mega-link-downloader-bot
```
```sh  
pip3 install -r requirements.txt
```
```sh  
cp sample_config.py config.py
```
```sh  
nano config.py
```
  - Now you will be inside the `config.py` file.
  - Then edit the values in it with your values! (Inside your `config.py` file you will see the examples of how to edit the fields.)
  - (For pasting letters, copy any value you want and take the curser to the place you want by arrow keys and right click the mouse! 😅)
  - After editing all with appropriate values as mentioned in the config file press Ctrl + X from your keyboard.
  - Then press y in your keyboard.
  - Then execute the below command. 👇
  
```sh  
python3 bot.py
```
Now If you did everything correctly, the bot will be running successfully! 🥳
</details>

---

## Variables
- `API_ID` -  Get this value from https://my.telegram.org/apps
- `API_HASH` - Get This Value from https://my.telegram.org/apps
- `TG_BOT_TOKEN` - Make a bot from https://t.me/BotFather and enter the token here.
- `Mega_email` - This is not necessary! Enter your mega email only if you have a mega.nz account with pro/business features.
- `Mega_password` - This is not necessary! Enter your mega password only if you have a mega.nz account with pro/business features.
- `Bot_username` - Your bot's telegram username. (must enter with '@' in the front of the username)

---

### Reason for making this open source :-

First of all I am an absolute noob😇🥺 (You can ensure it if you see the code even just once😂)

So when I was going through github in search for finding a mega link downloader bot code or a plugin in <b>pyrogram</b> I found nothing!🥺😞

<strike>(Cat userbot and ultroid userbot has a mega link downloader plugin. Also mirror bots have the mega link download feature but none of them were pyrogram.)</strike>
(Update :- After my bot many other bots/codes got created! 😂)

I didn't wan't to change the [@mysterious_uploader_robot](https://t.me/mysterious_uploader_robot) 's whole base to telethon just for the feature of downloading mega links!😑😒 So I decided to make a plugin on my own, based on pyrogram. 🤷‍♀️

The code was originally made as a plugin for my [@mysterious_uploader_robot](https://t.me/mysterious_uploader_robot) but thought to make a separate bot for downloading mega.nz links!

<b>For the help of any guy like me in this world who is wondering how to make a bot for downloading mega links, or for whoever that is finding a code to download mega links; thought to make this public. 😇❤️</b>

---

## Credits, and Thanks to

* [AnyDLBot](https://github.com/SpEcHiDe/AnyDLBot) of [SpEcHlDe](https://telegram.dog/ThankTelegram) for the base code that I have used for this.
* [Odwyersoftware](https://github.com/odwyersoftware) for the awesome [Python library](https://github.com/odwyersoftware/mega.py) of [mega.nz-API](https://mega.nz/API)
* [Nexa Bots](https://t.me/Nexa_bots) beacuse I got an example idea of how to add a download progress message, from their [forked mega.nz-API code.](https://github.com/Itz-fork/pyro-mega.py)
* [Dan](https://github.com/delivrance) for [pyrogram](https://github.com/Pyrogram)

<b>Project written and created by</b> - [XMYSTERIOUSX](https://github.com/XMYSTERlOUSX)

---

#### LICENSE

- GPLv3
