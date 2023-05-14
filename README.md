# CSGOPredictor

*Context of the game:* CS:GO is a tactical classic shooter game. There are plenty of game modes, but for this model I picked only Competitive Mode data. In this mode, there's two teams (CT and Terrorist) with 5 players each team. They play for a best of 30 rounds (16 rounds winner wins the game) and each round is limited to 1 minute and 55 seconds. At the start, one team plays as CT and the other as Terrorist. After 15 rounds played, the teams swap side. This dataset holds only 8 different maps from the game. You win a round as Terrorist by either planting the bomb and making sure it explodes, or by eliminating the other team. You win a round as CT by either eliminating the other team, or by disarming the bomb after it was planted.

The goal of the project is to select and create the best prediction algorithm to predict which of the two teams of the game will win the round, depending on previous results and their decisions preparing for the round. This is the last project of Machine Learning Models course.
#### Structure of the notebook:
* `Libraries`: Includes a briefly description of where they were used in the process and some functions I wrote
* `Data`: Includes the data export, separation in train-test and exploration
* `Cleaning and Full Pipelines`: Building the two pipelines that I used
* `Models`: Building the pipeline where I'm placing my model after trying a bunch of them