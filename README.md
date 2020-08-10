# ModMail
Self hosted premade ModMail bot for Discord servers written in Discord.js. Enter some info in the config.json and start the bot!

# Config
```json
{
    "token": "BOT_TOKEN",
    "server_id": "000000000000000",
    "channel_prefix": "modmail",
    "modmail_viewing_role_id": "000000000000000",
    "status": "DM to Contact Staff",
    "modmail_category_name": "Modmail",
    "display_mod_name": false
}
```
This is the default configuration file. We will go over each line and how to fill it in.

(make sure you have developer mode enabled by going to Settings > Appearance > Developer Mode in Discord)

`"token": "BOT_TOKEN"`: You will need a developer bot token for this line. You can get it on the [Discord Developers Application Page](https://discord.com/developers/applications). Click on New Application, click Bot, then click Add Bot. You will then get a token which you can copy into this field.

`"server_id": "000000000000000"`: Right click the server that you want to use the bot and and click Copy ID.

`"channel_prefix": "modmail"`: The prefix for each channel for modmail. If you leave it at default a channel will look like this: `modmail_username_userid`

`"modmail_viewing_role_id": "000000000000000"`: The ID for the role that can view ModMail channels. Go into server settings > Roles > Right click the role > Copy ID

`"status": "DM to Contact Staff"`: The bot's status.

`"modmail_category_name": "Modmail"`: The name of the category to put ModMail channels in.

`"display_mod_name": false`: Whether or not to display the responding moderator's username in the mod messages. Leaving it at `false` will result in the username being `Anonymous#0000`.

# Installation
1. Download and install [NodeJS](https://nodejs.org/)
2. Download and install [Git](https://git-scm.com/)
3. Clone this repository by right clicking a new folder, clicking `Git bash here`, and pasting in `git clone https://github.com/JohnodonCode/modmail.git`.
4. Open command prompt in the folder with the `index.js` file and run `node index.js`
