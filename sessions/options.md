# Session Options

Session options are added when using the `=play` command. They modify the behaviour of the bot when playing a quiz.

For more information on using the `=play` command, [see this page](../commands/quizzes.md#play-id-options).

For a quick way to modify session options, click "Play" on a quiz on the [web interface](https://quizbot.xyz) to bring up a play command generator.

## `delete`

Deletes all messages in the quiz after they are used. This reduces clutter in the channel, but you won't be able to see past quizzes.

## `no_leaderboards`

Hide all leaderboards during the quiz except the final leaderboard.

## `no_answers`

Don't display the correct after each question.

## `shuffle`

Shuffle the order of the quiz questions.

## `shuffle_answers`

Shuffle the answers for each question.

## `nicknames`

When generating leaderboards, use server nicknames instead of usernames.

## `simple_scoring`

All questions will award 1 point for the correct answer and 0 points for an incorrect answer. This means that timing no longer affects points.

Note: even though points appear in this way on the quiz leaderboard, your actual points are always calculated using the default 500-1000pts system for the global leaderboard and stored in [your profile](https://quizbot.xyz/me).

## `hide_indicators`

Hide the position movement indicators when generating leaderboards.

## `competitive` **([PREMIUM](https://quizbot.xyz/premium))**

Run the quiz in competitive mode.

[More details available here.](https://quizbot.xyz/support/features/competitive)

## `report` **([PREMIUM](https://quizbot.xyz/premium))**

Generate a session report at the end of the quiz including a question-by-question breakdown of the results.

This is also enabled by default when competitive mode is enabled.
