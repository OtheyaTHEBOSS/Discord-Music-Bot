# 〽️Discord Music Bot
> A discord music bot that uses youtube.

This is the beginning of a discord music bot creation.
I will be working on a discord music bot similar to evobot that is able to get songs from youtube and play in discord vc.
_____________________________________________________________________________________________________________________________
# 📌 Requirement
- Discord (Token)
- Python
- (more elaboration soon)

# ⚙️Setup
## 🪟 Windows
1. Install python (if not installed)
``` sh
winget install Python.Python.3 --scope machine
```
2. Press shift and right-click in the folder with the Musicbot.py
3. Create a new virtual environment and open it
``` sh
python -m venv discord

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
>> discord\\Scripts\\activate
```
4. Download dependencies
``` sh
pip install discord.py[voice] yt-dlp

winget install ffmpeg
```
5. Run code
``` sh
python Musicbot.py
```

## 🐧 Linux
1. Right-click and open terminal in the folder
2. Create a new virtual environment and open it
``` sh
python3 -m venv discord

discord/bin/activate
```
3. Download dependencies
``` sh
sudo apt update

sudo apt install ffmpeg

pip install discord.py[voice] yt-dlp
```
4. Run code
``` sh
python Musicbot.py
```

## 📱 Android
1. Download Termux from Playstore
2. Download dependencies
``` sh
pkg update && pkg upgrade

pip install discord.py yt-dlp

pkg install python ffmpeg

pkg install clang python libffi openssl libsodium

SODIUM_INSTALL=system pip install pynacl

pip install nano
```
3. Create the code in Termux venv
``` sh
nano Musicbot.py
```
4. Copy code and paste into the nano editor, then press ```ctrl + x``` followed by ```y``` and ```enter``` to close it
3. Run code
``` sh
python Musicbot.py
```
# 🛠️ Config
Copy token from discord dev portal and paste it on the code

# 📜 Features
- Play
- Pause
- Resume
- Stop

# 🚀 Coming soon
- so much more features
- buttons to control
- better ui
- maybe try use the new pycord library
- gimme ideas...
