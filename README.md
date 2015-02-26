# brobbot-instance

See [brobbot-slack-instance](https://github.com/b3nj4m/brobbot-slack-instance) to easily deploy an instance of brobbot for your Slack room.

### Download and install

Create an instance of [brobbot](https://npmjs.org/package/brobbot) by downloading a [release](https://github.com/b3nj4m/brobbot-instance/releases) and installing dependencies:

```bash
curl https://codeload.github.com/b3nj4m/brobbot-instance/tar.gz/1.0.6 | tar -xz
cd brobbot-instance-1.0.6
npm install
./index.sh [args]
```

You will probably want to install an adapter. E.g. for Slack:

```bash
npm install --save brobbot-slack
BROBBOT_SLACK_TOKEN=myslacktoken ./index.sh -a slack
```

See [the docs](https://github.com/b3nj4m/hubot/blob/master/docs/README.md) for more info.
