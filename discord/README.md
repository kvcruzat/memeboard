# Team JLEI - Discord Purge Roast Bot

This is a bot for Discord based on the [Airhorn Bot](https://github.com/hammerandchisel/airhornbot/).

The bot allows you to play sound fragments from Dota 2 esports to your Discord voice channel.

# Installation

1. Install Go Lang for your platform. See https://golang.org/doc/install#install
2. Set up your $GOPATH System Variable as described at https://golang.org/doc/install#testing
3. Fire up a console or command prompt and download the Discord RoastBot: `go get github.com/kvcruzat/memeboard/discord/cmd/bot`
4. Install (compile) the MemeBot: `go install github.com/dorsath/roastboard/discord/cmd/bot`
5. Go to your $GOPATH\bin folder and copy the audio folder to the current folder: `cp -r ../src/github.com/kvcruzat/memeboard/discord/cmd/bot/audio/ .` (sorry not arsed to figure out how to automate this..)
6. Create a Discord bot and add it to your Server using the Discord Developers API as described at https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token. Save your Bot token for the next step!
7. Navigate to your $GOPATH\bin folder and fire up the bot!
  * For windows: ./bot.exe -t **bot-token** -o **owner-id**
  * For Linux/OSX: ./bot -t **bot-token** -o **owner-id**
8. The Bot should now have joined your Server, ready to meme!

# How To Use

**^help** to show available categories
**^help CAT** to show available sounds
Example usage: **^donger power**
