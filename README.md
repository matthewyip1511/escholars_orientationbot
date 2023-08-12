# NUS E-Scholars Orientation 2023 Telegram Bot

Hello! This is the repository for the telegram bot that I made for the Engineering Scholars Orienation 2023. 

This started out as an idea to automate points addition for the station games, and in a way that teams would be able to track their scores in real time. Over time more functions were added, and eventually the bot was able to:

1. Track Scores for each team
2. Send broadcast messages to all users
3. Automate a trivia game, where Orientation Groups (OG) are able to play the game within the bot and be credited points automatically based on their scores
4. Track and approve side quests sent in by teams, with the wild cards awarded automatically to the teams as well


The bot was hosted on a raspberry pi during the course of the orientation, but this can be hosted on a server as well should that be required. 


For a list of commands:

/start - for the user to start the bot, where the user will be able to see his role and OG number in the orientation

/checkteams - for users to see the total state of play and how many points each team has

/myteam - for users to check information for their own teams

/addpoints - for game masters and exco members to add points for teams

/broadcast - for admins to send out broadcast messages to all users

/side_quest - for users to send in side quests for approval by the admins

/start_game_trivia - for users to start the automated trivia game 

/help - for help with the bot




