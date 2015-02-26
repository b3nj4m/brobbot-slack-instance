# brobbot-slack-instance

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Create an instance of [brobbot](https://npmjs.org/package/brobbot) for your Slack room by downloading a [release](https://github.com/b3nj4m/brobbot-instance/releases) and installing dependencies:

```bash
curl https://codeload.github.com/b3nj4m/brobbot-slack-instance/tar.gz/1.0.0 | tar -xz
cd brobbot-slack-instance-1.0.0
npm install
BROBBOT_SLACK_TOKEN=myslacktoken ./index.sh -a slack -b redis -s google,google-image,quote,react
```

See [the docs](https://github.com/b3nj4m/hubot/blob/master/docs/README.md) for more info about brobbot.
