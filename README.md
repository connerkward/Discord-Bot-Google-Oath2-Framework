# Google-Fit-Discord-Bot
Flask, Authlib, Discord Webhook, Google Oauth 2.0 API

Flip peer pressure to your advantage! This Discord bot posts weekly calorie-burned counts to your group chat. 

Currently:
  -> user enters website
  -> user authorizes app through google oauth landing page
  -> server accesses user data (google fit calories burned)
  -> server parses json data reccieved 
  -> server sends formatted message to discord webhook
