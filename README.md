![HUNTER](https://i.imgur.com/N2Ru7ib.jpg)

# Hunter Alpha

A modular Telegram Python bot running on python3 with a sqlalchemy database and an entirely themed persona to make Naruto suitable for Anime and Manga group chats. 

Can be found on telegram as [Hunter Alpha (bot)](http://t.me/xxXhunteralphaX_Bot).

The Support group can be reached out to at [Hunter Alpha Support](https://t.me/AlphaEliasxd), where you can ask for help about [Hunter Alpha (bot)](https://t.me/xxXhunteralphaX_Bot), discover/request new features, report bugs, and stay in the loop whenever a new update is available :) 


## How to setup/deploy.

### Read these notes carefully before proceeding 
 - Edit any mentions of [@Hunter Alpha Support](https://t.me/AlphaEliasxd) Support to your own support chat
 - Your code must be open source and a link to your fork's repository must be there in the start reply of the bot [See this](https://github.com/AlphaEliasPY/AlphaHunter)
 - Lastly, if you are found to run this repo without the code being open sourced or the repository link not mentioned in the bot, we will push a gban for you in our network because of being in violation of the license, you are free to be a dick and not respect the open source code (we do not mind) but we will not be having you around our chats
 - This repo does not come with technical support, so DO NOT come to us asking help about deploy/console errors


<details>
  <summary>Steps to deploy on Heroku !! </summary>

```
Fill in all the details, Deploy!
Now go to https://dashboard.heroku.com/apps/(app-name)/resources ( Replace (app-name) with your app name )
REMEMBER: Turn on worker dyno (Don't worry It's free :D) & Webhook
Now send the bot /start, If it doesn't respond go to https://dashboard.heroku.com/apps/(app-name)/settings and remove webhook and port.
```
<a href="https://heroku.com/deploy">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
[Generate String Session](https://replit.com/@SpEcHiDe/GenerateStringSession)  << Select telethon

### Mandatory Vars 📒
```
[+] Make Sure You Add All These Mandatory Vars. 
    [-] API_ID:   You can get this value from https://my.telegram.org
    [-] API_HASH :   You can get this value from https://my.telegram.org
    [-] STRINGSESSION : Your String Session, You can get this From Repl or BY running String_Gen File Locally
    [-] MONGO_URI : Your Mongo DB DataBase Url. .
    [-] TOKEN: Get from botfarther
    [-] DATABASE_URL: from elephantsql.com
    [-] OWNER_ID: ur id
    [-] MONGO_PORT: 27017
    [-] MONGO_DB': 'DaisyX'
    [-] REDIS_URI: from redislabs.com (remove port)
    [-] REDIS_PORT: At the end of uri
    [-] REDIS_PASS: pass
[+] The HunterAlpha won't run without setting the mandatory vars.
```
