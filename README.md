# swa_tracker
SWA Tracker

## Usage:
### First Step
Type the flight you want to track in the file ```trip_list```
Example:
```
ORD:PHX:2023-03-03
MDW:PHX:2023-03-03
```
```
<Departure>:<Arrival>:YYYY-MM-DD
```
### Second Step
Replace ```ChatID``` and Telegram API ```token``` in ```tele_bot.py```

If you have question on Telegram Bot, the following resources might helps
[How to create a telegram bot]("https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0")

To get Telegram Bot ChatID, you should...
1. Use your browser to open following link
2. replace ```<YourBOTToken>``` with your own token.
3. ```https://api.telegram.org/bot<YourBOTToken>/getUpdates```
4. Then send a message to a Telegram bot
5. Refresh the website. You should get the json included chatid

### Tohttps://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0
Warning: This maynot work in some Chrome version. SW will also upgrade their cyber security features. The code still working on Jan 19, 2023. Submit a issue if it is not working anymore.
