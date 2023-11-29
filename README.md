# gpt-api-test

## Progress

Good prompt engineering tactics

1. Tactic: Include details in your query to get more relevant answers

2. Tactic: Ask the model to adopt a persona

3. Tactic: Specify the steps required to complete a task

4. Tactic: Provide examples

5. Tactic: Specify the desired length of the output

6. Strategy: Provide reference text

7. Tactic: Use intent classification to identify the most relevant instructions for a user query

8. Tactic: For dialogue applications that require very long conversations, summarize or filter previous dialogue

9. Tactic: Summarize long documents piecewise and construct a full summary recursively

10. Tactic: Instruct the model to work out its own solution before rushing to a conclusion

11. Tactic: Use inner monologue or a sequence of queries to hide the model's reasoning process

12. Tactic: Ask the model if it missed anything on previous passes

13. Tactic: Use embeddings-based search to implement efficient knowledge retrieval

14. Tactic: Give the model access to specific functions

15. Strategy: Test changes systematically

16. Tactic: Evaluate model outputs with reference to gold-standard answers

Takeaway after doing testings

1. Maybe stop GPT from including its reason. Example
Given that the player is currently 10 steps away, I would start by using the ":Rage:" skill. This skill doesn't deal damage, but it adds a fun element to the game. So, my response would be:

2. Let GPT know it can choose to do nothing

3. Let GPT know it can choose to move closer to the player

4. Let GPT know more clearly about how it should play the game: aggressively to win or laid back to wait or some level in between.

5. During actual game programming for the boss, at the same time, write prompts to let GPT knows it has that ability

6. Since the delay is large between question and response. Maybe a turn-based game would be a better suit.

7. GPT might repeat an action if the scenario doesn't change. Let it know that it should varies its response to the context or how it should dealt with the repeated action from players.

8. To make the GPT AI actually unpredictable to play against, we have to instruct it with special character, motivation and actions.

9. Clarify the terms to the GPT AI. For example, if we tell the AI to react with Rage when the boss receives high damage. GPT AI won't know what does high damage mean.

10. Be careful of GPT ability to handle mathematical movement. Use words to let GPT knows it can do a certain thing and wether its position matters.

11. In order to make GPT boss truly flexible, we need it to have a lot of personal characteristic and a big pool of moves.
