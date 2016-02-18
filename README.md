retweetBot
===========

##Setup
1. Install dependecies.
'pip2 install tweepy'
2. make a copy of config.json.sample to config.json
3. make a copy of textrc.json.sample
4. Complete thr fields of the two json files.
5. Run it or push it to heroku
 **Run Locally**
`python bot.py'

##Push To Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://www.heroku.com/deploy/?template=https://github.com/rnavagamuwa/retweetBot)

**OR**

```
git add .
git add config.json -f
git add textrc.json -f
git commit -m "init heroku"
git push heroku master
```

Features
--------
###Status Tweet
Every 3 hours a Status tweet is send with the tags, the bot is listening in.
###Random Tweet
Every 5 hours tweets a text defined in the `textrc.json`
###Ad Tweet
At defined intervals will tweet defined text in `textrc.json`

