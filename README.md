## For Support join here [MoviezOnlySupport](https://telegram.dog/moviezonlysupport)
## Working example group [Leech Here](https://telegram.dog/leechtorrentmoviesonly)

# Telegram Torrent Leecher 🔥🤖

### A Telegram Torrent (and youtube-dl) Leecher based on [Pyrogram](https://github.com/pyrogram/pyrogram)

### This is a leech to FILE repo! Leech to STREAM(video) availabe here > [Patch-1](https://github.com/prgofficial/TorrentLeech-GDriVe/tree/patch-1)


# Benefits :-
    ✓ Telegram File mirrorring to cloud along with its unzipping, unrar and untar
    ✓ Drive/Teamdrive support/All other cloud services rclone.org supports
    ✓ Unzip
    ✓ Unrar
    ✓ Untar
    ✓ Custom file name
    ✓ Custom commands

### Credit goes to SpEcHiDe for his [Publicleech](https://github.com/SpEcHiDe/PublicLeech) repo & GautamKumar for his [repo](https://github.com/gautamajay52/TorrentLeech-Gdrive)

## Installing

### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/prgofficial/TorrentLeech-GDriVe)


### The Legacy Way

Simply clone the repository and run the main file:

```sh
git clone https://github.com/SpEcHiDe/PublicLeech.git
cd PublicLeech
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create config.py appropriately>
python3 -m tobrot
```

### an example config.py 👇
```py
from tobrot.sample_config import Config

class Config(Config):
  TG_BOT_TOKEN = ""
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  AUTH_CHANNEL = -1001234567890
```


### YOU NEED UNLIMITED TEAM/SHARE DRIVE IN ORDER TO USE THE GDRIVE FUNCIONS Flawlessly (normal GDRIVE has 15 gb of storage only)

##### Set Rclone

1. Download Rclone from Here > [DOWNLOAD](https://rclone.org/downloads/)
2. Extract the downloaded zip file and run cmd(hold shift and right click) from the Extracted folder.
3. RUN rclone config and follow the onscreen instructions!
4. If done Correctly, you'll get some thing like this in the cmd ;

    type = drive
    client_id = 55965362181-5105rlkk8dq8ej3iopmfc0.apps.googleusercontent.com
    client_secret = VOqihw0cqXPCdDo7UR
    scope = drive
    token = {"access_token":"ya29.a0ASMA0zZmcJHRao_Et9YqPrSRq0hZBdVElo4TUIP_1R6DJx4vWzd-        00MbrlZdmH3sTRnOYhseTsEqKXcBfleu4yTfpeTJjAmaUCYkIsYuEsj608ncZEM3QZVnjnA7c7-    TeI","token_type":"Bearer","refresh_token":"1//0gOjRXzVHCgYIARAAGBASNwF-L9IrdBJRlXXUqUvOES7H4Ge3UDhy7mJLvJcROd9XQsI6e8zJsHQ88cw","expiry":"2020-07- 02T10:17:13.1076684+02:00"}
    team_drive = 0AAHdpck9PVA 

5. Copy these entries from CMD and paste it in ' RCLONE_CONFIG ' {heroku var}  - Don't try to copy paste the above string; It wont work 🤣.


##### Set IndexURL

1. Go to https://gdindex-code-builder.glitch.me/, and follow its instructions. Copy the code!
2. Go to https://dash.cloudflare.com/c8bf985554bb03b455f683f8cafe25f2/workers/new and login/signup.
3. Paste the code in script section. Then save and deploy.
4. You'll get your GDIndex link.
5. Add new key in HEROKU Vars - ' INDEX_LINK '  and add the above index link as value

HOPE Everything will be working by now!
For any support ping me here  >  [MoviezOnlySupport](https://telegram.dog/moviezonlysupport)

## FAQ

* `INDEX_LINK`: (Without `/` at last of the link, otherwise u will get error) During creating index, plz fill `Default Root ID` with the id of your `DESTINATION_FOLDER` after creating. Otherwise index will not work properly.

## Available Commands

* `/ytdl`: This command should be used as reply to a [supported link](https://ytdl-org.github.io/youtube-dl/supportedsites.html)

* `/leech`: This command should be used as reply to a magnetic link, a torrent link, or a direct link. [this command will SPAM the chat and send the downloads a seperate files, if there is more than one file, in the specified torrent]

* `/leech archive`: This command should be used as reply to a magnetic link, a torrent link, or a direct link. [This command will create a .tar.gz file of the output directory, and send the files in the chat, splited into PARTS of 1024MiB each, due to Telegram limitations]

* `/gleech`: This command should be used as reply to a magnetic link, a torrent link, or a direct link. And this will download the files from the given link or torrent and will upload to the drive using rclone.

* `/gleech archive` This command will compress the folder/file and will upload to your google drive.

* `/leech unzip`: This will unzip the .zip file and dupload to telegram.

* `/gleech unzip`: This will unzip the .zip file and upload to drive.

* `/leech unrar`: This will unrar the .rar file and dupload to telegram.

* `/gleech unrar`: This will unrar the .rar file and upload to drive.

* `/leech untar`: This will untar the .tar file and upload to telegram.

* `/gleech untar`: This will untar the .tar file and upload to drive.

* `/tleech`: This will mirror the telegram files to ur respective cloud drive.

* `/tleech unzip`: This will unzip the .zip telegram file and upload to drive.

* `/tleech unrar`: This will unrar the .rar telegram file and upload to drive.

* `/tleech untar`: This will untar the .tar telegram file and upload to drive.





## Credits, and Thanks to
* [Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [Robots](https://telegram.dog/Robots) for their [@UploadBot](https://telegram.dog/UploadBot)
* [@AjeeshNair](https://telegram.dog/AjeeshNait) for his [torrent.ajee.sh](https://torrent.ajee.sh)
* [@gotstc](https://telegram.dog/gotstc), @aryanvikash, [@HasibulKabir](https://telegram.dog/HasibulKabir) for their TORRENT groups
* [![CopyLeft](https://telegra.ph/file/b514ed14d994557a724cb.jpg)](https://telegra.ph/file/fab1017e21c42a5c1e613.mp4 "CopyLeft Credit Video")
