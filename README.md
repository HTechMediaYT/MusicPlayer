# Telegram Voice Chat Bot with Channel Support.

A Telegram Bot to Play Audio in Voice Chats With Youtube and Jio Saavn support.
Supports Playing Music files from a telegram channel.
Supports Live streaming from youtube.

  </a>
</p>
<p align="center">
  <a href="https://github.com/HTechMediaYT/MusicPlayer/stars">
    <img src="https://img.shields.io/github/stars/HTechMediaYT/MusicPlayer?label=Star&style=social"
  </a>
  
  <a href="https://github.com/HTechMediaYT/MusicPlayer/fork">
    <img src="https://img.shields.io/github/forks/HTechMediaYT/MusicPlayer?label=Fork&style=social">
  </a>  

---
    
<p align="center">
  <a href="https://www.youtube.com/channel/UCrAM4Fg0zn7uLgAAfII-SWQ">
    <img src="https://img.shields.io/badge/youtube-grey?style=for-the-badge&logo=youtube"/>
  </a>
  <a href="https://github.com/HTechMediaYT">
    <img src="https://img.shields.io/github/followers/HTechMediaYT?label=GitHub&logo=github&style=for-the-badge&color=blue"/>
  </a>  
</p>  
<p align="center">  
  <a href="https://instagram.com/h_tech_media">
    <img src="https://img.shields.io/badge/Instagram-grey?style=for-the-badge&logo=instagram"/>
  </a>
  <a href="https://www.facebook.com/HTechMediaYT">
    <img src="https://img.shields.io/badge/facebook-grey?style=for-the-badge&logo=facebook"/>
  </a> 
  <a href="https://telegram.me/HTechMedia">
    <img src="https://img.shields.io/badge/Telegram-grey?style=for-the-badge&logo=telegram"/>
  </a>
  <a href="https://telegram.me/HTechMediaSupport">
    <img src="https://img.shields.io/badge/Support-grey?style=for-the-badge&logo=telegram"/>
  </a>  
</p>

---


```
Please fork this repository don't import code
Made with Python3
Copyright permission under MIT License
License -> https://github.com/HTechMediaYT/MusicPlayer/blob/master/LICENSE

```

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/HTechMediaYT/MusicPlayer)

NOTE: Make sure you have started a VoiceChat in your Group before deploying.
### Deploy to VPS

```sh
git clone https://github.com/HTechMediaYT/MusicPlayer
cd MusicPlayer
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 main.py
```

## Vars:

1. `API_ID` : Get From my.telegram.org

2. `API_HASH` : Get from my.telegram.org

3. `BOT_TOKEN` : @Botfather

4. `SESSION_STRING` : Generate From here [GenerateStringName](https://repl.it/@subinps/getStringName)

5. `CHAT` : ID of Channel/Group where the bot plays Music.

6. `LOG_GROUP` : Group to send Playlist, if CHAT is a Group

7. `ADMINS` : ID of users who can use admin commands.

8. `STREAM_URL` : Stream URL of radio station or a youtube live video to stream when the bot starts or with /radio command.You can also use a telegram channel as radio station. Just upload all you music files to a telegram channel and add the bot and user account in that channel and use chat_id of channel in STREAM_URL.You can also use any public telegram channels, in that case use the username of such channel in place of STREAM_URL (Bot being admin in public channel not required.)  [Some Streaming Links](https://gist.github.com/HTechMediaYT/40f65a421ee558db2e243a425f20eea4)

9. `MAXIMUM_DURATION` : Maximum duration of song to play.(Optional)

10. `REPLY_MESSAGE` : A reply to those who message the USER account in PM. Leave it blank if you do not need this feature. 

11. `ADMIN_ONLY` : Pass `Y` If you want to make /play and /splay commands only for admins of `CHAT`. By default /play and /splay is available for all.


- Enable the worker after deploy the project to Heroku

- Bot will starts radio automatically in given `CHAT` with given `STREAM_URL` after deploy.(24*7 Music even if heroku restarts, radio stream restarts automatically.)  

- To play a song use /play as a reply to audio file or a youtube link.

- Use /play <song name> to play song from youtube and /splay <song name> to play from JioSaavn or /cplay <channel username or channel id> to play music from a telegram channel.

- Use /help to know about other commands.

  
**Features**

- Playlist, queue.
- Supports Play from Youtube Playlist.
- Change VoiceChat title to current playing song name.
- Supports Live streaming from youtube
- Supports both Jio Saavn and youtube to search songs.
- Play from telegram file supported.
- Play whole music files from a telegram channel.
- Starts Radio after if no songs in playlist.
- Automatically downloads audio for the first two tracks in the playlist to ensure smooth playing
- Automatic restart even if heroku restarts.

```
Contributions are welcomed, But Kanging and editing a few lines wont make you a Developer.
Fork the repo, Do not Import code.

```
  
```
LEGAL DISCLAIMER

Developer or his team won't be liable for any loss caused by MISUSE of this Script.
This Bot is Indended to be used only for Educational Purposes.

```
#### Support


## Credits 
- [Dash Eclipse's](https://github.com/dashezup) for his [tgvc-userbot](https://github.com/callsmusic/tgvc-userbot).
- [Thuhin](https://github.com/cachecleanerjeet) for his [Jio Saavn API](https://github.com/cachecleanerjeet/JiosaavnAPI).
- [subinps](https://github.com/subinps/MusicPlayer)

  #### Made With ❤ By [@HTechMedia](https://telegram.dog/HTechMedia)    
