## hubot-karma-classic [![NPM version](https://badge.fury.io/js/hubot-karma-classic.png)](http://badge.fury.io/js/hubot-karma-classic)

A [Hubot](https://github.com/github/hubot) plugin to track arbitrary karma.

### History

Officially the karma plugin originally distributed with hubot and later via
hubot-scripts has been deprecated and hubot-plusplus was offered as a replacement.

Sadly hubot-plusplus did not import our old karma and often choked under rapid
successive commands which I found unsuitable.  So here's the classic karma script
repackaged in the new npm package style format.  Use as you will.

### Usage

    <thing>++ - give thing some karma
    <thing>-- - take away some of thing's karma
    hubot karma <thing> - check thing's karma (if <thing> is omitted, show the top 5)
    hubot karma empty <thing> - empty a thing's karma
    hubot karma best - show the top 5
    hubot karma worst - show the bottom 5

### Installation (new style):

1. cd into your hubot dir, run `npm install --save hubot-karma-classic` (adds a dependency in package.json).
2. Add `"hubot-karma-classic"` to your `external-scripts.json` file.
3. Restart Hubot.

### Installation (old style):

Place hubot-karma-class.coffee to your hubot/scripts directory. Restart hubot.
