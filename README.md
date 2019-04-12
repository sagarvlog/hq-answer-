# HQ Answers Bot
### Crowdsourced HQ Trivia Discord Bot

Invite this discord bot to your server and it will automatically collect answers from users whenever an HQ game is live. It will display everybody's answers nicely in any channel you specify.

### Installation
```
$ git clone https://github.com/FastestMolasses/HQ-Answers.git
$ cd HQ-Answers
$ pip install -r requirements.txt
$ touch config.py
```

Your `config.py` file should look like this. Enter the relevant information.

```
DISCORD_TOKEN = 'NTY0Njc3ODI0OTg0NjQ1NjMy.XLAcng.ypl3Mm7NCd9DFUF3np_b8D1R5s0'
CHANNEL_ID = 510323894633365524 # Should be the channel you want the bot to post in. Leave as int.
```
