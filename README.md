# SWA Tracker

Warning: This maynot work in some Chrome version. SW will also upgrade their cyber security features. 
The code still working on Feb 23, 2023. Submit a issue if it is not working anymore.

### Running Examples:
<img width="402" alt="Screenshot 2023-02-23 at 2 36 54 PM" src="https://user-images.githubusercontent.com/37731817/221024368-86f8cdf3-1725-4de0-903c-43c4183943a7.png">


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


### Telegram Bot Help
##### How to create a Telegram Bot?
[How to create a telegram bot](https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0)

##### How to find the Chat ID?
To get Telegram Bot ChatID, you should...
1. Use your browser to open following link
2. replace ```<YourBOTToken>``` with your own token.
3. ```https://api.telegram.org/bot<YourBOTToken>/getUpdates```
4. Then send a message to a Telegram bot
5. Refresh the website. You should get the json included chatid


