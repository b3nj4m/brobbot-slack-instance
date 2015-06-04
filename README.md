# brobbot-slack-instance

Create an instance of [brobbot](https://npmjs.org/package/brobbot) for your Slack room with a few useful scripts included:

- [brobbot-redis-brain](https://npmjs.org/package/brobbot-redis-brain) - a Redis-backed brain for your brobbot
- [brobbot-slack](https://npmjs.org/package/brobbot-slack) - a Slack adapter for your brobbot
- [brobbot-google](https://npmjs.org/package/brobbot-google) - a Google search script for your brobbot
- [brobbot-google-image](https://npmjs.org/package/brobbot-google-image) - a Google image search script for your brobbot
- [brobbot-google-image-bomb](https://npmjs.org/package/brobbot-google-image-bomb) - a Google image search script for your brobbot which returns a bomb of images
- [brobbot-quote](https://npmjs.org/package/brobbot-quote) - a quote/remember script for your brobbot
- [brobbot-react](https://npmjs.org/package/brobbot-react) - a hear/react script for your brobbot
- [brobbot-youtube](https://npmjs.org/package/brobbot-youtube) - a YouTube search script for your brobbot

### Deploy with Heroku button
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Download and run locally

Download a [release](https://github.com/b3nj4m/brobbot-instance/releases) and install dependencies:

```bash
curl https://codeload.github.com/b3nj4m/brobbot-slack-instance/tar.gz/3.0.0 | tar -xz
cd brobbot-slack-instance-3.0.0
npm install
BROBBOT_SLACK_TOKEN=myslacktoken ./index.sh -a slack -b redis -s google,google-image,google-image-bomb,quote,react,youtube
```

See [the docs](https://github.com/b3nj4m/hubot/blob/master/docs/README.md) for more info about brobbot.
