#                    Inline-Filter-Bot

A Telegram Bot for filter in Inline

### Features

- Unlimited Filters
- Supports all type of filters
- Supports Alert Button
- Using Common Markups for formatting
- Import and Export feature (allows to copy filters from one inline filter bot to another)
- Custom Start Message, filter adding-deleting command

## DEMO BOT
<a href="https://t.me/fhinlinebot"><img src="https://img.shields.io/badge/Demo-Telegram%20Bot-blue.svg?logo=telegram"></a>

### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>

#### Deploy in your VPS
````bash
git clone https://github.com/NiranjanVRam/Inline-Filter-Bot
cd Inline-Filter-Bot
pip3 install -r requirements.txt
python3 InlineBot
````
##
### Special Commands

#### Admin Commands
* `/add` - add filter to bot (customisable command)
* `/del` - delete filter from bot (customisable command)
* `/filters` - view current filters
* `/export` - export filters data as file
* `/stats` - view bot statistics
* `/broadcast` - broadcast any messages to bot users

#### Owner Commands
* `/delall` - delete all filters from bot
* `/import` - import an exported file to bot
* All other admin commands

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `ADMINS` Other Admins Telegram Id, seperate by space
* `DATABASE_URL` Database URL from mongodb.com
* `THUMBNAIL_URL` Optional: URL of an Image, thumbnail for Text filter
* `IS_PUBLIC` Optional: Set this False if you creating this bot admins only, Default is True
* `START_MESSAGE` Optional: Your Bot Start Message, you can use HTML, and fillings for formatting
* `FILTER_COMMAND` Optional: Custom command for add filter
* `DELETE_COMMAND` Optional: Custom command for add filter

#### Fillings for START_MESSAGE
* `{mention}` Mention user
* `{first_name}` User First name
* `{last_name}` User Last name
* `{user_id}` Telegram ID of the User
* `{username}` Username of the User

## Support   
Join Our [Telegram Group](https://t.me/fhsupportgrp) For Support/Assistance And Our [Channel](https://t.me/fileshomeofficial) For Updates.   
   
Report Bugs, Give Feature Requests There..   

### Credits

- Thanks to [Dan](https://github.com/delivrance) for His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks to [Mahesh](https://github.com/Mahesh0253) for this [Repo](https://github.com/Mahesh0253/Media-Search-bot)
- Thanks to [๓คгςยร](https://github.com/prgofficial) and [ᎫᎪᏟᏦ](https://github.com/Jack-of-tg) for [Unlimited Filter Repo](https://github.com/TroJanzHEX/Unlimited-Filter-Bot)

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  
##

   **Star this Repo if you Liked it ⭐⭐⭐**
