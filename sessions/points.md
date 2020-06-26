# QuizBot Points System

QuizBot awards players points for each question they answer correctly with the bot.

## How points are calculated

QuizBot calculates your points per correct answer using the following formula.

Answering a question wrong always awards 0 points.

`points_awarded = max_points - ((max_points - min_points) / time_allowed) * time_taken`

Note: if the `simple_scoring` option is enabled, both min_points and max_points will be 1.

## Default values

By default, a players will receive 500 - 1000 points for each correct answer.

## Changing the min/max points for a question

Both the [QuizEditor](../quizzes/quizeditor.md) and [web interface](https://quizbot.xyz) allow you to edit the minimum/maximum points per question.

## Note about stored points

During quiz sessions, the leaderboards will display points based on any custom min/max values/options that have been applied to the questions.

When a quiz ends, users' points are added to their profile to generate global leaderboards and other stats.

QuizBot will calculate these saved points on a "normalized" scale. It will use the default 500 - 1000pts system. This means that changing the points per question or using the `simple_scoring` session option won't affect your leaderboard position or allow to you gain/lose points on your profile.
