The following are the basic Discord moderation commands that you will need to know how to use.

> All moderation actions should be done either by using Carl-bot or manually. DO NOT use other bots like Dyno or Arcane to enforce disciplinary punishments.

Since [Discord has released slash commands](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ), we would be utilizing them instead of using normal chat commands. 

> As long as Carl-bot's chat commands are still there, we can still use them.

# List of Commands

Type  `/moderation`  and you can view a list of Carl-bot's moderation commands. You will mostly use commands on this list. Some Carl-bot moderation commands overlap with existing Discord default slash commands or functions. You could choose either to use Carl-bot's or Discord's default slash command. You could also always right click on the member to view a list of actions you can enforce.

> Note that using Carl-bot moderation commands will send a DM message to the offender, while using Discord's default slash commands will not.

![Image](https://media.discordapp.net/attachments/709662217934471170/1126228926189015120/screenshot-2022-12-26-at-12-45-24-pm.png)

> It is completely fine to use these moderation commands in chat - don’t worry about going into a hidden channel to use them. 

### Warnings

* `/moderation warn` - Warns a member. This warning will be recorded.

* `/moderation warns` - Checks the warnings received by a member

* `/moderation clearwarnings` - Removes all warnings from a member

* `/moderation removewarning` - Removes a warning, specify using the case ID which could be found by the `/moderation warns` command

### Mute

Muting is depreciated in the server as often when we create new channels we have to also include the mute role in the channel permission to avoid creating loopholes. It is very time-consuming and little to no people are muted currently. Therefore, please use timeout instead.

> Do not use any mute commands as it no longer works!

![Image](https://media.discordapp.net/attachments/709662217934471170/1126229184902078515/screenshot-2022-12-26-at-2-08-38-pm.png)

* `/timeout` - The default Discord timeout function

* `/moderation timeout` - Prevents the member from chatting, adding reactions, and joining voice channels

* `/moderation removetimeout` - Removes the timeout applied on a member

### Kick

* `/kick` - The default Discord kick function

* `/moderation kick` - Removes the member from the server (can still join back)

### Ban

* `/ban` - The default Discord ban function

* `/moderation ban` - Bans a member permanently

* `/moderation tempban` - Bans a member for a specific duration

* `/moderation unban` - Lifts the ban of a member

* `/moderation softban` - Bans and immediately unbans a member (Similar to kicking)

* `/moderation massban` - Bans a list of members

### Dead Chat Ping

Want to revive the chat? Ping the  _Dead Chat Ping_  by using  `=dead`  in the chat!

### Lock Chat

Use `=lock` to prohibit anyone except admins 

### Purging Messages

Sometimes you may want to delete lots of messages because it is harmful. You can use `=purge 10` (replace 10 with the amount of messages you want to delete)

## Reminder:

There are still countless of useful bot commands we haven't covered yet. We recommend you checking out [Carl-bot's documentation](https://docs.carl.gg/) and familiarise yourself with other bot's commands.
