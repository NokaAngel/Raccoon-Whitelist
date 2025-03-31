# Raccoon Whitelisting
<img src="https://profile-counter.glitch.me/Raccoon-Whitelist/count.svg" />
Need support? Join the Discord, and make a ticket I'll be happy to help when available. https://discord.gg/RxHQjtg7c8

## What is Raccoon Whitelisting?
Raccoon Whitelisting is a new whitelist script, created by TheRaccoon (PeEcEeChIP) for an easy-to-use Discord whitelist. This script uses [Badger's](https://github.com/JaredScar) [Discord API Script](https://github.com/JaredScar/Badger_Discord_API), refraining from having to make another Discord bot token, and grab role ID's, making this whitelist script easier to use for anybody.

## Dependencies Needed
[Badger Discord API](https://github.com/JaredScar/Badger_Discord_API)

## Configuration
```
-- Change your server whitelist configurations here.
Configure = {
DiscordKick = 'We couldn\'t detect the desktop client of Discord, please check if your Discord is open.', -- Sends message to the user if they're Discord is not open.
WhitelistKick = 'We\'re sorry, but this server has been whitelisted. Please join the Discord and check how to be whitelisted.', -- Sends message to the user if they're not whitelisted in the server.
RoleIDKick = 'Sorry, but we couldn\'t detect your Role ID\'s. If this problem persist\'s please contact the server developer/development team.',
svname = 'Server Name',
Whitelisted = { -- Roles that you assigned in Badgers API that should pass the whitelist, make sure each role is listed with a comma.
    "Whitelisted Role #1",
    "Whitelisted Role #2",
    "Whitelisted Role #3",
},
}```
