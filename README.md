# modmail

**Fork this public repository, make it private and commit some changes to *config.json* file.**

For example:
```
{
  "prefix" : "<your prefix>",
  "ServerID" : "<your guild/server ID (remember to enable Developer mode in Discord to get ID)>",
  "TOKEN" : "<your bot token (make this repo private first!)>",
  "ACT" : "<your bot activity status (it can be PLAYING, WATCHING, STREAMING, LISTENING and all must be capitals)>",
  "STT" : "<your subtext next to bot activity (it could be anything you like)>"
}
```

### Host on heroku.com (as if you don't know how to)


#### Heroku

- Create an app
- Connect your forked private repository to heroku app
- Enable *Automatic Deploy* and *Deploy* your app.
- Come to tab *Resources*, unselect *web npm start* and enable *worker node index.js*
- Check the bot in your server!

#### Tasks

- [ ] Easy to host on heroku.
- [x] Main function.
- [ ] Custom prefix.
