# Bot manual for Discord

## Bot Invitation Link - [Click on me](https://discord.com/api/oauth2/authorize?client_id=583233909211267072&permissions=2148392129&scope=bot)

**ATTENTION - In order for the bot to work on the server, you must submit an application for verification. You can submit it here ---> [Submit a request for server verification](https://docs.google.com/forms/d/1YBB72PuJw3GGwKzqIlxuBeXeFMajOL0vVb84iLrTog8).**

## Introductory part:

- **Bot prefix** - *is a dot symbol.*
- **Description of the bot's work** - *the bot checks all the arrived server participants for the presence of their **ID** in our database. If this **ID** is found, the bot sends a message about this incident to the designated channel.*

## Commands for owners of verified servers:

- **.addmoder ID** - *instead of **ID**, enter the **ID** of the participant you want to appoint as a moderator in the bot. Where to get a user or server **ID** is described in this article - [Where to find the participant ID in Discrod](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-).*
- **.delmoder ID** - *removing a participant from a moderating role in the bot.* 
- **.channel ID** - *the purpose of the channel where the bot will send notifications.*
- **.rechannel ID** - *reassigning the bot channel.*

## Commands of moderators assigned in the bot:

**ATTENTION - A moderator assigned on one server cannot use the bot on the second server !**

- **.check ID** - Forced check request **ID**

## Common commands:

- **.help** - *Displays the help about the bot*
- **.status** - *Displays the number of verified servers and records in the database*
