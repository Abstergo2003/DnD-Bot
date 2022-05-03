# DnD Bot
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
IMPORTANT: READ THIS BEFORE RUNNING BOT OR ADDING IT TO YOUR ERVER
################################################################################################################
INTRODUCTION

Hello,
This server contains DnD features! You can: throw dices, create channels for your own games (role 'game-master' needed, ask admin)
and invite people to play with you!

To create game room (role 'game-master' needed)
1. type /sgame 'name of game' to create your own channel and voice channel
2. to add people type /add @'nick' (don’t worry no one else than you wont be able to add or remove people)
3. to remove people type /remove @'nick'
4. to end game (and delete channel) type /dgame on this channel

There exists special channel visible only for people wanting to play (having role 'invite-me')
1. To get this role type /waiting
2. To remove this role type /notwaiting

Reacting to message sent on 'class' channel will give you role depending on your reaction
(use as favourite class marker)
1. to remove role (favourite class) type /del 'Role' (mind capital letters)

To throw dices
1. To dice 4 use /d4
2. To dice any other number use analogic command
3. Available dices 4,6,8,10,12,20,100
4. To throw multiple dices use /md4 "count" (analogical every other dice)
5. To throw custom dice type /cd "max value" (when using /mcd "max value" "count")
6. Every number has assigned color

Randomizers:
/rfight generates random fight with random opponent, to see scheme type !fhelp
/rmeet generates random side quest (his beginning), to see scheme type !mhelp
/rdeath 'user' chooses random death for user (in ‘user’ field you can type whatever you want), to see scheme type !dhelp
/rmname genrates random male name
/rfname genrates random female name

#################################################################################################################
CONFIGURATION:
1. enter https://discord.com/developers/applications
2. create your bott aplication
3. find app id and bot token
4. open 'bot directory'/data/settings.json
5. insert previously gathered data in indicated fields 
6. save file
##################################################################################################################
Running bot

1 method on your computer
- install node.js and open it
- type node 'bot directory'/bot.js
- done
- add bot to your server

2 method on heroku (free)
- create Procfile and put it in bot's directory
- in procfile type 'worker: node bot.js'
- deploy bot to heroku
- change dyno formation to worker 
- add bot to your server
- done

To add bot to your server insert this url in your web browser: https://discord.com/api/oauth2/authorize?client_id='your_app_id'6&permissions=8&scope=bot%20applications.commands
#######################################################################################################################

Youre welcome to insert your own changes to this bot but it was created using Discord Bot Maker so it might be really hard to do without this tool, 
Any true programmer should rather try writting his own bot from scratch.

####################################################################################################################
