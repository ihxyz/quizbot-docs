# Managing the bot's permissions

Having issues with permissions? See [this article](https://support.discordapp.com/hc/en-us/articles/206029707) from Discord for support.

## Required permissions

The bot requires all of the following permissions in a channel to run correctly:

- Read messages
- Send messages
- Embed links
- Add reactions
- Read message history
- Use external emojis
- Manage messages

All of these permissions should appear when on the bot invite page.

## Limiting the bot to one channel

To limit the bot to one channel, you must deny its "Read Messages" permissions in all other channels. This prevents commands being executed in those channels.

For each channel you don't want the bot to execute commands in:

- Open the channel settings by clicking the settings icon near the channel name
- Select "Permissions" from the menu on the left
- Add the "QuizBot" role to the list of overridden permissions
- Deny the "Read Messages" permission.

Do not remove the "Read Messages" permission from channels where you want to allow command execution.
