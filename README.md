# Keyforge Card command
This is setup to use "/card" followed by the name of a KeyForge card in order to locate the respective image link
inside the card list JSON file provided by keyforgegame.com, and then post it in the assigned slack channel.

As of right now, it does not do any form of advanced search. It even requires you to spell the card name correctly
(although you can ignore case). I would like to improve upon the search better in future updates.
# About
Using the [KeyForge API](https://www.keyforgegame.com/api/decks/?page=1&links=cards) to make the local JSON file.

Made possible by the helpful bot template from [Easy Peasy Slash Commands](https://medium.com/slack-developer-blog/easy-peasy-slash-commands-getting-started-c37ff3f14d3e#.nfr4px2vi)

See [Slack API](https://api.slack.com/slash-commands) guide for more information on slash commands.
