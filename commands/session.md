# Quiz Session Commands

**Note:** This page uses command notation. [Learn what this means](../notation.md).

## `=play <id> (options)`

- `<id>`: the ID of the quiz. You get this when searching for a quiz, or creating your own.
- `(options)`: (OPTIONAL) a list of options, separated with spaces.

Play a quiz in the current channel.

## `=stop (id)`

- `(id)`: (OPTIONAL) the session ID to stop. If none is provided, the session in the current channel will be used.

Stop a quiz session. This immediately ends the quiz.

## `=pause (id)`

- `(id)`: (OPTIONAL) the session ID to pause. If none is provided, the session in the current channel will be used.

Pause a quiz session. This means the bot will wait until resumed to continue to the next question.

You cannot pause a quiz session during a question. You must wait until the correct answer or leaderboard is being displayed.

## `=resume (id)`

- `(id)`: (OPTIONAL) the session ID to resume. If none is provided, the session in the current channel will be used.

Resume a quiz session after it is paused with `=pause`.
