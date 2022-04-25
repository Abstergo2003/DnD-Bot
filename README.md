# dice-roller
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
IMPORTANT: READ THIS BEFORE RUNNING BOT OR ADDING IT TO YOUR ERVER
################################################################################################################
INTRODUCTION

This is bot with DnD features, you can throw dices, create your own game rooms (having special role, ask admin how to get it)
and invite people to play with you!

To create game room (role 'game-master' needed)
1. type !sgame to create your own channel
2. to add people type !add @'nick' (dont worry no one else than you wont be able to add or remove people)
3. to remove people type !remove @'nick'
4. to end game (and delete channel) type !dgame on this channel

There exists special channel visible only for people wanting to play (having role 'invite-me')
1. To get this role type !waiting
2. To remove this role type !notwaiting

Reacting to message sent on 'class' channel will give you role depending on your reaction
(use as favourite class marker)
1. to remove role (favourite class) type !del 'Role' (mind bigg letters)
!!!Attention!!!: for this option to work your channel needs emoji called as in class channel message [every possible dnd class (without addons), every emoji should be named only with small letters]
!!!Attention!!!: every time bot is restarted it resend message to class channel
please delete previous one.

Randomizers:
!rfight generates random fight with random opponent, to see scheme type !fhelp
!rmeet generates random side quest (his beginning), to see scheme type !mhelp
!rdeath 'user' chooses random death for user (in ‘user’ field you can type whatever you want), to see scheme type !dhelp
!rmname genrates random male name
!rfname genrates random female name

To throw dices
1. To dice 4 use !d4
2. To dice any other number use analogic command
3. Avalible dices 4,6,8,10,12,20,100
4. To throw multiple dices use !md4 "count" (analogical every other dice)
5. To throw custom dice type !cd "max value" (when using !mcd "max value" "count")
6. Every number has assigned color
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

To add bot to your server insert this url in your web browser: https://discordapp.com/oauth2/authorize?client_id='your aplication id'&scope=bot&permissions=2146958591
#######################################################################################################################

Youre welcome to insert your own changes to this bot but it was created using Discord Bot Maker so it might be really hard to do without this tool, 
Any true programmer should rather try writting his own bot from scratch.

####################################################################################################################