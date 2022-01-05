# Simple discord music bot

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

### Requirements

1. Server to run on
2. Discord Bot token
3. python 3.5->

### Setup for Ubuntu 18.04

```
sudo apt update
sudo apt install git ffmpeg python3-pip
git clone https://github.com/bobtus/music-bot ~/music-bot
cd ~/music-bot
pip3 install -U discord.py pynacl youtube-dl
```

Paste Discord Bot Token inside main.py
```
nano main.py
```
Press down to get to the last line and replace token with your discord bot token. `bot.run('token')`

Press Ctrl+X to exit

Type y and Press Enter to save

Run using:
```
python3 main.py
```
