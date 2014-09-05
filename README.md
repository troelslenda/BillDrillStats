# BillDrillStats

## Server

A server based app. REST? Maybe it should be build with Sympfony.

User verification via login

POST new score with time 345. Future, 1, 2, 3, 4, 5, 6 shot. + distance in meters. + user + time/date. Possibly attaching a photo as documentation.

GET own stats with time and date filtered by distance.

GET top 20 highscores.

POST login.

## The iOS app

App should have a startup screen with highscores if connected to a service. Else it should show connection configuration.

Tabs at bottom, start (highscores), new entry, my scores.

### New entry.

An INT input field with a moving comma in order to show decimals. You input 345 and it automatically corrects it to 3,45 as a cash register.

An int for distance. The distance should be remembered from last entry.

If no user is verified, the login should be prompted before entry possible.

### My Scores.

A list of all scores ordered by best time.

If no user is verified, the login should be prompted before entry possible.