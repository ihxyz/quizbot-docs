# Quiz Schedules

**Note: this is a "beta" feature and may not be entirely stable yet.**

QuizBot v2.7.0 introduced a new feature: the ability to schedule quizzes at a set interval or time.

## Creating a schedule

Run `=schedule create` to create a new quiz schedule. This will also start the schedule editor.

Right now, the number of schedules is limited for non-premium users to prevent abuse.

## Using the schedule editor

Edit a schedule by running `=schedule edit <id>`. This will create an embed showing details about the schedule and how to modify them.

### Channel

The channel in which quiz sessions will be started by the schedule. [Note that the bot will need the standard permissions defined here.](../admin/permissions.md)

### Start time

When the first session will be started by the schedule.

The start time needs needs to be in the following format: `YYYY-MM-DD HH:mm`

### Quizzes

A list of quiz IDs the schedule will go through and run.

You can only add quizzes you have access to.

### Selection mode

How the bot will decide which quiz to run next. There are currently two modes:

- `random`: quizzes are selected randomly.
- `order`: quizzes are ran in the same order they're added.

### Interval

How often a session is started by the schedule.

### Repeats

How many times the schedule will run and start a quiz. Premium members can set this to infinity.

### Notification

A custom role or mention to notify when a session is about to be started.

The `@here` and `@everyone` mentions can also be used.
