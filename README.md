# brobbot-instance

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Create an instance of [brobbot](https://npmjs.org/package/brobbot) by downloading a [release](https://github.com/b3nj4m/brobbot-instance/releases) and installing dependencies:

```bash
curl https://codeload.github.com/b3nj4m/brobbot-instance/tar.gz/1.0.0 | tar -xz
cd brobbot-instance-1.0.0
npm install
./index.sh [args]
```

You will probably want to install an adapter. E.g. for Slack:

```bash
npm install --save brobbot-slack
BROBBOT_SLACK_TOKEN=myslacktoken ./index.sh -a slack
```

See [the docs](https://github.com/b3nj4m/hubot/blob/master/docs/README.md) for more info.
