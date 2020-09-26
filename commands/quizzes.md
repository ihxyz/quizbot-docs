# Quiz Commands

**Note:** This page uses command notation. [Learn what this means](/commands/notation.md).

## `=create-quiz <name>;<description>`

- `<name>`: the quiz name.
- `<description>`: a description of the quiz.

Create a quiz. This will automatically start a [QuizEditor](../quizzes/quizeditor.md).

## `=edit <id>`

Edit a quiz.

For more information, see the [QuizEditor page](../quizzes/quizeditor.md).

## `=featured`

Show a list of public featured quizzes.

## `=search <query ...>`

Search all QuizBot public quizzes.

You can also do this via the [web interface](https://quizbot.xyz/explore) for a cleaner results page.

## `=view <id> (correct) (start-end)`

- `<id>`: the quiz ID to view.
- `(correct)`: (OPTIONAL) if you are the quiz owner, add `correct` after the ID to highlight the correct question answers.
- `(start-end)`: (OPTIONAL) specify a start and end question to display if the quiz has many questions.

View a quiz.

You can also do this via the web interface by clicking a listed quiz.

## `=spreadsheet`

Import a quiz from a CSV spreadsheet.

For more information, run `=spreadsheet help` or watch our [YouTube tutorial](https://youtu.be/4bcpmbIlrPw).
