# Mobile-Game-User-Retention-AB-Testing

## Description
This project will examine user retention for the mobile puzzle game [Cookie Cats](https://tactilegames.com/games/cookie-cats/) by Tactile Entertainment using A/B Tests. The game introduces gates at certain levels that require a player to wait a certain time period or make an in-app purchase to progress further. Initially, the gate was placed at level 30 but we're going to analyze an A/B Test where the gate was moved to level 40. The tests will check if there's a difference in player retention for users in 1 and 7 day periods between the two gates.

## Dataset
The data comes from [Kaggle](https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats?resource=download]) and is also used in a DataCamp course. The variables are:

* `userid`: A unique number that identifies each player
* `version`: Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40)
* `sum_gamerounds`: the number of game rounds played by the player during the first 14 days after install
* `renention_1`:  Did the player come back and play 1 day after installing?
* `retention_7`: Did the player come back and play 7 days after installing?

