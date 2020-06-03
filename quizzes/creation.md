# Creating and editing quizzes with QuizBot

There are three methods to create or edit a quiz with QuizBot.

## Method 1: Create a quiz on the web interface

The simplest and most common way to create a quiz is with [QuizBot's web interface: https://quizbot.xyz](https://quizbot.xyz).

To create a quiz, go to [this page](https://quizbot.xyz/quizzes/list). Log in and select "Create a new quiz". This should take you to the quiz editor page, where you can modify the quiz name, description, colour, access level and add/remove questions. Once you're done, make sure to click "Save".

To edit an existing quiz, navigate to the [same page as above](https://quizbot.xyz/quizzes/list) and then select "Edit" next to the quiz you want to edit.

## Method 2: Create a quiz using commands

You can also create quizzes entirely using commands, without leaving Discord.

To create a quiz run the `=create-quiz` command in a channel which QuizBot has access to.

When creating a quiz you will always need to give the quiz a name. If you wish you can also give the quiz a description. The command you are executing should look something like this: `=create-quiz Name;Description`.

If you are having issues check that the bot has all the [required permissions](/admin/permissions.md).

Once you have created your quiz you will see a QuizEditor which allows you to change all of your quizzes' settings as well as adding questions. See how to use the QuizEditor [here](quizeditor.md)

## Method 3: Import a quiz from a CSV spreadsheet

Finally, you can convert a quiz from a spreadsheet to a QuizBot quiz. This is done through the `=spreadsheet` command. For more information, run `=spreadsheet help` or watch our [official Youtube tutorial](https://youtu.be/4bcpmbIlrPw).
