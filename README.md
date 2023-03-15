# ChatGPT Bot  

[![wakatime](https://wakatime.com/badge/github/Aleksey-Voko/ChatGPT_Bot.svg)](https://wakatime.com/badge/github/Aleksey-Voko/ChatGPT_Bot)

Telegram-bot (Python, [aiogram](https://aiogram.dev/), [OpenAI API](https://platform.openai.com/docs/api-reference/))

The simplest telegram bot for dialogue with ChatGPT.  
Requires OpenAI API token for authorization.  
Prepared for deployment on [Railway](https://railway.app/)  

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/13afTa?referralCode=S5A3Zn)

#### Variables

- `BOT_TOKEN` - Telegram Bot Token  
- `RAILWAY_APP_NAME` - Part of the URL with the name of the application. (After Deploying go to 'Settings' of the project and press on "Generate Domain". It'll generate a domain for your app. Just copy `yourdomainname.up` (Yeah, don't copy the rest :) and this will be a value for your `RAILWAY_APP_NAME`.  
- `CHAT_ID` - ID of the telegram chat where the bot is allowed to work. You can add more chat IDs, just take a look at `WORKS_CHATS` in the file [`config.py`](chat_gpt_bot/config.py) and add available environment variables on your railway app with user IDs
- `AI_KEY` - OpenAI API Token
