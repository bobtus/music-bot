# Simple discord music bot

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

### Requirements

1. Server to run on
2. Discord Bot token
3. python 3.5->

### Setup for Ubuntu 18.04

Paste discord bot token into .env file

```
sudo apt-get install build-essential unzip -y
sudo apt-get install software-properties-common -y
sudo apt-get install git ffmpeg libopus-dev libffi-dev libsodium-dev python3-pip
git clone https://github.com/bobtus/music-bot ~/music-bot -b master
cd ~/music-bot
sudo python3 -m pip install -U pip
sudo python3 -m pip install -U discord.py pynacl youtube-dl
```

Run uning:
```
python3 main.py
```
