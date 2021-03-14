# QuizBot Currency (Q$)

***Please note that the data and information on this page is subject to change and may not be updated immediately.***

The QuizBot Currency, referred to as `Q$`, is earned by playing quizzes and can be spent on new items like profile backgrounds in the [item shop](shop.md)

## How is Q$ earned

Every QuizBot user starts with 0 Q$ when their account is created.

You can earn Q$ by reaching certain level milestones, (more information can be found [here](../levelling/xp.md#quizbot-q))

### Playing quizzes 

Currency is only awarded during quizzes with **more than 2 players.**

The amount of Q$ a player earns depends on their position on the leaderboard. 

For instance, if a player is in the top 5% of players, they will earn 1500 Q$, if they are in the top 50%, they will still earn 300 Q$. 

Part of the list of rewards is shown below to give a general idea of the distribution (some steps are omitted):  

- Top 5%: 1500 Q$
- Top 20%: 700 Q$
- Top 40%: 500 Q$
- Top 60%: 250 Q$
- Top 80%: 175 Q$

Note: These rewards do **NOT** add up, i.e. Although a top 5% player is also in the top 20%, they will only get 1500 Q$ and not 1500 Q$ + 700 Q$ + ...

The amount of Q$ rewarded is also reduced if any of the below factors apply to you:

- You own the quiz being played (x0.2 multiplier)
- You started the quiz session (x0.2 multiplier)

These reductions stack with each other.

### Having your quizzes played

If you have high-quality quizzes which are often played by other people, you may also earn Q$ this way.

If a session has **more than 4 players,** you will earn a set amount of Q$ plus a bonus for the amount of plyers playing.

##### Formula
If `player_count` > 4:

`reward = 100 + (min(player_count, 100) * 10)`
