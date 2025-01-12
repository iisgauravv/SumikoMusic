<h1 align="centre">SumikoMusic</h1>

### A bot that can play music on Telegram Group and Channel Voice Chats
#### POWERED BY [PYTGCALLS](https://github.com/pytgcalls/pytgcalls)


<p align="center">
  <img src="https://telegra.ph/file/5f3177b9e24763db285d5.jpg">
</p>

<h2> Whats new 🔥 </h2>

- Thumbnail Support
- Playlist Support
- Current playback support
- Showing track names when skipping
- Zero downtime, Fully Stable
- DEEZER,YOUTUBE & SAAVN PLAYBACK SUPPORTED
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.



## The easiest way to deploy this Bot
### HEROKU
<a href="https://heroku.com/deploy?template=https://github.com/iisgaurav/SumikoMusic"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

### StringSession

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@iisgaurav/AuraXVCBot#main.py) 

### ⚔ Self-hosting (For Devs) 
```sh
# Install Git First (apt-instll git)
$ git clone https://github.com/iisgaurav/SumikoMusic
$ cd SumikoMusic
# Upgrade sources
# Install All Requirements 
$ pip(3) install -r requirements.txt
# Rename example.env to local.env and fill
$ npm i -g npm
# Start Bot 
$ python(3) -m SumikoMusic
```

### Commands for Group 🛠
#### For all in group

- `/play <song name>` - play song you requested
- `/play <reply to audio>` - play replied file
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly

#### Admins only.
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list

### Commands for Channel Music Play 🛠
For linked group admins only:
- `/cplay <song name>` - play song you requested
- `/cplay <reply to audio>` - play replied file
- `/cdplay <song name>` - play song you requested via deezer
- `/csplay <song name>` - play song you requested via jio saavn
- `/cplaylist` - Show now playing list
- `/cccurrent` - Show now playing
- `/cplayer` - open music player settings panel
- `/cpause` - pause song play
- `/cresume` - resume song play
- `/cskip` - play next song
- `/cend` - stop music play
- `/userbotjoinchannel` - invite assistant to your chat
* channel is also can be used instead of c

If you don't like to play in linked channel:
 1. Get your channel ID.
 2. Rename your group to: Channel Music: your_channel_id
 3. Add @SumikoMusicBot as Channel admin with full perms
 4. add helper to channel
 5. Simply send commands in your group.


## Support
- [Channel](https://telegram.dog/VCBots)
- [Group](https://telegram.dog/VCSupport)





### Credits
#### Special Credits
- [Rojserbest](http://github.com/rojserbest): Callsmusic Developer

This bot is based on the original work done by [Rojserbest](http://github.com/rojserbest). Without his hardwork SumikoMusic won't exist. 
SumikoMusic is a modified version of [Callsmusic](https://github.com/callsmusic/callsmusic)

#### Contribtors
- [iisgaurav](https://github.com/iisgaurav): Dev
- [AuraXNetwork](https://github.com/AuraXNetwork/AuraXMusicBot)
- [SumikoMusic](https://github.com/TeamOfDaisyX/SumikoMusic)
- [Hamker Cat](https://github.com/thehamkercat/)
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
- [Original Repo owners](https://github.com/suprojects/CallsMusic)
