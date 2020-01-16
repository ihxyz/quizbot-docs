# Playing quizzes

First, you will need a quiz ID.
You can get this by either [creating your own quiz](creation.md) or [finding a quiz on our web interface](https://quizbot.xyz/quizzes/search).

## The play command

To play a quiz, run `=play <id>` (e.g. `=play 1`). You can specify one or more option after the ID, as follows.

## Options

### delete

Deletes all messages in the quiz after they are used. This reduces clutter in the channel, but you won't be able to see past quizzes.

### no_answers

Do not show the correct answer after each question.

### no_leaderboards

Do not show leaderboards after each question, only the final leaderboard.

### competitive

[Premium only.](https://quizbot.xyz/premium)

Players submit answer via DM, rather than through reaction. This eliminates cheating.
Also, a final "quiz report" is generated and sent to the user who started the quiz. This contains a question-by-question breakdown of each user's answer and time, as well as all leaderboards.
