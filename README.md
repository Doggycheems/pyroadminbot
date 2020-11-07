
[Credits](https://github.com/pyroadminbot/pyroadminbot#credits-and-thanks-to) 

# Bot 🔥🤖

A Telegram Bot ~~[still WIP, not stable]~~ based on [Pyrogram](https://github.com/pyrogram/pyrogram)

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [COPYING](./COPYING) for more details.

## installing

#### the normal way 👍👍👍
 
 git clone https://github.com/pyroadminbot/pyroadminbot.git
 cd pyroadminbot
 rename sample_config.py to config.py
 and edit config.py
 bash startbot
 or python3 -m pyrobot


#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## ENVironment VARiables

#### Mandatory Environment Variables

* `TG_BOT_TOKEN_BF_HER`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.

* `APP_ID`
* `API_HASH`: Get these two values from [my.telegram.org/apps](https://my.telegram.org/apps).
  * N.B.: if Telegram is blocked by your ISP, try our [Telegram bot](https://telegram.dog/UseTGXBot) to get the IDs.

#### Optional Environment Variables

* `ENV`: set this to `ANYTHING` if you want to use ENVIRON mode.

* `COMMAND_HAND_LER`: the default value is `/`, which is the recommended value. Change this only __if__ you know what you are doing.

* `TMP_DOWNLOAD_DIRECTORY`: the path (as a string) to store the temporary files, which are used by some of the plugins.

* `HEROKU_API_KEY`: this is only required if you are going to use Heroku, for the `/update` plugin to work.

* `OFFICIAL_UPSTREAM_REPO`: this is only required if you are going to use Heroku, for the `/update` plugin to work.

* `DATABASE_URL`: ~~if you are using Heroku, this value is automatically filled by the Postgres Plugin.~~ if you are not using Heroku, Read the guide on how to Install Database?, in [the Wiki](https://github.com/SpEcHiDe/PyroGramBot/wiki/How-to-Install-Database-%3F). **[**  __to be deprecated__ **]**

* `TELEGRAM_URL`: create a Telegram Channel / Super Group, with you robot as administrator, and add the channel id as an integer in this variable.

* `G_DRIVE_CLIENT_ID`: check [the Telegram Channel](https://t.me/UniBorg/48) for Instructions on Setting up Google Drive.

* `G_DRIVE_CLIENT_SECRET`: check [the Telegram Channel](https://t.me/UniBorg/48) for Instructions on Setting up Google Drive.

* `OWNER_ID`: this is not used currently, and might be used in the future.

* `SUDO_USERS`: The Telegram user_ids who should be allowed to use the sensitive features of the robot.

* `TG_IRU_S_M_ID`: this is used for the `sretlif` plugins.

* `WARN_DATA_ID`: this is used for the `warns` plugins.

* `WARN_SETTINGS_ID`: this is used for the `warns` plugins.



## Credits, and Thanks to

* [Dan Tès](https://github.com/delivrance) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [Colin Shark](https://github.com/ColinTheShark) for his [PyroBot](https://git.colinshark.de/PyroBot/PyroBot)
* [SpEcHiDe](https://github.com/SpEcHiDe) for the majority of the code based on [pyrogrambot](https://github.com/SpEcHiDe/PyroGramBot)
* [Skuzzy xD](https://github.com/SkuzzyxD) for the speedtest plugin from [telepyrobot](https://github.com/SkuzzyxD/TelePyroBot)
* [pokurt](https://github.com/pokurt) for the translate plugin from [Butler-Plus-Bot](https://github.com/pokurt/Butler-Plus-Bot)
* [Amano Team](https://github.com/AmanoTeam) for the sed plugin from [EduuRobot](https://github.com/AmanoTeam/EduuRobot)
* [![CopyLeft](https://telegra.ph/file/b514ed14d994557a724cb.jpg)](https://telegra.ph/file/fab1017e21c42a5c1e613.mp4 "CopyLeft Credit Video")
