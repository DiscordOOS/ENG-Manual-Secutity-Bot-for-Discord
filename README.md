# Bot manual for Discord

## Bot Invitation Link - [Click on me](https://discord.com/api/oauth2/authorize?client_id=583233909211267072&permissions=277025475648&scope=bot%20applications.commands)

**ATTENTION - In order for the bot to work on the server, you must submit an application for verification. You can submit it by entering the command /registration**

## Introductory part:

- **Description of the bot's work** - *the bot checks all the arrived server participants for the presence of their **ID** in our database. If this **ID** is found, the bot sends a message about this incident to the designated channel.*

## Commands for owners of verified servers:

- **/force** - *a command to force check all server participants to check for the presence of records about them in the database* **- WARNING This command will be available for execution once every 2 hours.**
- **/addmoder ID** - *instead of **ID**, enter the **ID** of the participant you want to appoint as a moderator in the bot. Where to get a user or server **ID** is described in this article - [Where to find the participant ID in Discrod](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-).*
- **/delmoder ID** - *removing a participant from a moderating role in the bot.* 
- **/channel ID** - *the purpose of the channel where the bot will send notifications.*

## Commands of moderators assigned in the bot:

**ATTENTION - A moderator assigned on one server cannot use the bot on the second server !**

- **/check ID** - Forced check request **ID**

## Common commands:

- **/help** - *Displays the help about the bot*
- **/status** - *Displays the number of verified servers and records in the database*

## New features:

- **New feature from 07/15/2021** - *Now, when a new ID is entered into the database, the bot automatically checks all verified servers, and if it finds this user on your server, it notifies you about it in the assigned channel.*
- **New feature from 07/21/2021** - *add new command .force*
- **New feature from 07/24/2021** - *add new command .prefix*
- **Global bot changes from 07/29/2022** - *Optimization of the bot, from this date all bot commands will work through /*
