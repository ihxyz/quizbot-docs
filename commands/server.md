# Server Management Commands

**Note:** This page uses command notation. [Learn what this means](/commands/notation).

## `=settings`

Configure basic settings for your server.

### `=settings prefix <prefix>`

Change the bot's command prefix for your server.

### `=settings language <language>`

Change the bot's language in your server.

[To see a list of supported languages, click here.](../i18n/languages.md)

## `=access-level`

Configure command access levels for your server.

Running this with no subcommand will list the current command access levels for your server.

### `=access-level set <command> <role|permission|disabled>`

Set command access levels. You can specify multiple commands by separating them with a semicolon (`;`).

- `<command>`: the name of the command to modify the access level for
- `role`: mention a role to lock a command to this role and higher.
- `permission`: lock a command to a Discord permission by prefixing it with `permission:`. E.g. `=access-level set play permission:manage_messages`.
- `disabled`: disable this command in your server.

### `=access-level reset <command>`

- `<command>`: the name of the command to reset the access level for

Remove the access level lock for one or more commands. You can specify multiple commands by separating them with a semicolon (`;`).
