# The Perfect Lil' Bot

This bot example is the combined work of members of the Discord.js and Idiot Guide's community.
It attempts to provide a "complete" starter example of a simple, one-file bot, with comments and
information to properly understand each part and how it works.

[Want a better tutorial? Check out AnIdiots.Guide](https://anidiots.guide/)

## Setup

> Before doing any of this make sure you have a bot account, check [this page](https://anidiots.guide/first-bot/your-first-bot) to know how to create the bot app and your token, as well as how to invite the bot in your guild.

- Create a new folder somewhere, give it a bot name, aka `MyBot` or `SuperBot`
- Create a file called `index.js`, and paste in the contents of index.js below.
- Create a file called `config.json` and give it the following content, using your real bot token:
```json
{ 
  "token"  : "MTg-this-IzNzU3OTA5NjA-is.not-DCeFB-a.real-r4DQlO-t0ken-qerT0",
  "prefix" : "+"
}
```

You then need to run a couple of things to make this work. Those things are run in console, which
can be opened by using `SHIFT+Right-Click` in your folder, and selected `Open command prompt here`
(your version of windows might say "PowerShell", don't worry it'll work fine!). In console, use
the following commands:

```
npm init -y
npm install discord.js
node index.js
```

If you've done things right, that should start the bot.

## Support
All support for bot code is offered in the Idiot's Guide Official Server. 

[![](http://proof.evie-banned.me/lasBU8E)](http://discord.gg/4NE4bk7)

**COMMENTS BELOW ARE NOT MONITORED AND YOU WILL NOT RECEIVE SUPPORT HERE**

## Credits

Project created and maintained with the help of: 

- **eslachance#4611** , aka `〈evie.codes〉`, for the heavy lifting
- **York#2400** , for pointing out mistakes, moral support and jester entertainment.
- **TrueBoxGuy#3692** for letting me know of a dumb thing I forgot, and an unfinished comment.