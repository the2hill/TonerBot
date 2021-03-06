# TonerBot [![Build Status](https://travis-ci.org/the2hill/TonerBot.svg?branch=master)](https://travis-ci.org/the2hill/TonerBot)

[List of commands](#commands)

## Requirements
1. Node
2. MongoDB

## Installation

*Note* - Windows 10 users may need to `npm install --global --production windows-build-tools` first

1. `npm install`
2. `mongod` if your database isn't started
3. Create `settings.js` using `example-settings.js`, replacing each variable with your credentials
4. `node index`

## Thanks
* [anjanms/DubAPI](https://github.com/anjanms/DubAPI) by [@anjanms](https://github.com/anjanms)
* [NitroGhost/dubbot-starter](https://github.com/NitroGhost/dubbot-starter) by [@NitroGhost](https://github.com/NitroGhost)
* [SteveBot](https://github.com/coryshaw1/SteveBot) by [@CoreyShaw](https://github.com/coryshaw1/SteveBot)

# [Commands](#commands)
Below are the list of commands that have been implemented.
## Categories

### Bot

* **!bot** - Bot responds with "I'm still here"
* **!ping** - Bot responds with "Pong!"
* **!pong** - Bot responds with "Ping!"
* **!thanks** - Bot responds with "You're welcome!"
* **!v** or **!ver** or **!version** - Bot responds with "Version: [*version number*]"

### Credits

##### Adding Credits
*Adding credits to a user is limited to one time per song.*
* **!fire** - Add to current DJ's total "props" count using a message of props as :fire:
* **!fire @username** - Add to @username's total "props" count using a message of props as :fire:
* **!love** - Add to current DJ's total "hearts" count :heart:
* **!love @username** - Add to @username's total "hearts" count :heart:
* **!props** - Add to current DJ's total "props" count using a message of props as :fist:
* **!props @username** - Add to @username's total "props" count using a message of props as :fist:
* **!tune** - Add to current DJ's total "props" count using a message of props as :musical_note:
* **!tune @username** - Add to @username's total "props" count using a message of props as :musical_note:

##### Credit Info
* **!balance** - See the amount of total "hearts" and total "props" connected to your name
* **!balance @username** - See the amount of total "hearts" and total "props" connected to @username
* **!leaders** - See the leaders of total "hearts" and total "props" in the database

### Fun
* **!cat** - Show a random cat picture or gif
* **!chuck** - Random Chuck Norris joke
* **!fact** - A random inciteful fact
* **!join** - Join a running raffle
* **!missuniverse** - Having a little fun with Steve
* **!raffle** - Force start a raffle. These normally happen randomly every 15-45 minutes.
    * *Note* - User that issued command must be a Manager or higher in room
* **!toner** - Help the rest of the room enjoy DubToner even more and see how clever he has become.
* **!todayfact** - A random inciteful fact about today
* **!gif** - A random gif
* **!(wilcard)** - Shows gifs related to search. ex: !help me

### Info
* **!commands** - Basic list of commands
* **!dubx** - Shameless plug to [sinfulBA/DubX](https://github.com/sinfulBA/DubX-Script)
* **!eta** - Gets the user's estimated time in minutes until their song plays
* **!help** - Basic list of commands
* **!lastplayed** or **!lastsong** or **!lasttrack** - Name and link of the song that just played
* **!link** - Get the current song's name and link.
    * *Note*: Get's the actual link of the song to SoundCloud instead of the api.soundcloud..../redirect link
* **!rules** - Rules of the room

### Moderation
##### For Mods and higher
* **!front @username** - Move @username to the front of the queue
* **!lock @username** - Lock/Pause @username's queue from playing
* **!lockskip** - Skip the current DJ, and lock/pause their queue. Useful for DJs that are AFK and continue to requeue
* **!pause @username** - Lock/Pause @username's queue from playing
* **!dj** - Force start DubToner as DJ. This check normally happens randomly every 2-5 minutes.
    * *Note* - User that issued command must be a Manager or higher in room

##### For Resident DJs and higher
* **!skip** - Skip the current song without reason or message using a reason of (broke, nsfw, op, theme, troll, and more to come) can leave blank if just want to skip without reason
* **!skip broke** or **!skip broken** - Skip the current song giving a reason that the song/video no longer exists or is unavailable in all countries
* **!skip nsfw** - Skip the current song giving a reason that the song/video is not safe for a work environment
* **!skip op** - Skip the current song giving a reason that the song/video is overplayed and banned from the room
* **!skip troll** - Skip the current song giving a reason that the song/video is trolling, *this also then kicks the DJ*


Much more to come, and suggestions are welcome! Please add an [issue](https://github.com/the2hill/TonerBot/issues) for any requests or bugs!
