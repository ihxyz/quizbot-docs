# Using the QuizEditor

**Note:** This page uses command notation. [Learn what this means](/commands/notation).

**Another note:** The QuizEditor command has multiple aliases. It is referred to as `=qe` here, but `=edit` and `=quiz-editor` also work.

## Initiating a QuizEditor

Before you can start editing a quiz within Discord you first need to start a QuizEditor. Grab the ID of the quiz you want to edit and run `=qe <id>`

## Changing quiz settings

You can use the QuizEditor to update general settings of your quiz.

The settings you can change are:

- Name
- Description
- Colour
- Tags

To change any of the first three settings use the command `=qe <setting> <new info>`.

For tags you can either add a tag (`=qe add-tag <tag>`) or remove a tag (`=qe del-tag <tag position>`)

## Adding and removing questions

You can also use the QuizEditor to add, edit or remove quiz questions.

To add a question run the command `=qe add-question`. This will open a new embed where you can change all the settings relating to the new question.

Similarly, you can edit a question by running the command `=qe edit-question`. Similar to add-question, this will also open a new embed with all the previous information of the question which you can update.

### `=qe question <question>`

Change what you are asking the player. This is required for every quiz question!

### `=qe add-answer <answer1>;(answer2;answer3...)`

Add new answers to the current question. To add more than one answer append a semicolon (`;`) to the first answer and add your next answer. This can be repeated multiple times.

Please note: Currently answers cannot include the semicolon character (`;`) when added through the QuizEditor. You can still include semicolons when editing a question on the [web interface](https://quizbot.xyz/quizzes).

### `=qe del-answer <answer number>`

Delete the answer at the given position from the list of answers.

### `=qe correct <answer number>`

Set the correct answer for the question.

Each question must have a correct answer and currently cannot have multiple correct answers.

### `=qe time <seconds>`

Set the amount of time, in seconds, which the players will have to answer the question before the answers are displayed.

### `=qe min <min points>`

Edit the minimum points awarded for this question.

[For more information on QuizBot's points system, see this page.](/sessions/points)

### `=qe max <max points>`

Edit the maximum points awarded for this question.

[For more information on QuizBot's points system, see this page.](/sessions/points)

### `=qe image <image url>`

[QuizBot Premium Exclusive Feature](https://quizbot.xyz/premium)

Set an image which will be displayed alongside the question.

[For privacy reasons we only accept a limited amount of hosting websites. To see the current list, check this page.](imagehosting.md)
