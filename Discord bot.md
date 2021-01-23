# Creating Discord Bot with Raspberry Pi

## Motivation

I have the Discord server for use while we participate in the CTF(Capture the Flag). To participate, we have to know the schedule for the CTF. But I don't want to search on Google. Then I remembered Python could make a Discord bot. Also, this looks fun.



## The purpose of bot

- To scrap the schedules from the [CTFtime](https://ctftime.org/).



## What did I use?

The following are some of the Things that I used to build the bot:

- Raspberry Pi 4 Model B
- Chromium(Chrome)
- Python3 and some modules like Selenium, discord.py, etc..



## Raspberry Pi

Raspberry Pi's role is to maintain the bot to continue running 24hrs in your network. It is connected to your home network and can be remotely accessed from a laptop.

I already installed the Raspberry Pi OS together with the pip and Chromium too. Then I updated and upgraded those and installed chromium-chromedriver with the next terminal command.

```
sudo apt-get install chromium-chromedriver
```

or find proper Chromedriver API from [Here](http://ports.ubuntu.com/pool/universe/c/chromium-browser/), then use wget command.

Finally, I was able to go smoothly, without any error.



## Python3

The bot is made up of two primary modules.

The first module is [Discord.py](https://pypi.org/project/discord.py/), which is used to connect the guilds(servers), set commands, and read guild, channel, and message data. And the second is Selenium, which is used for the scraping schedules from CTFtime.





## Reference

[Discord.py API](https://discordpy.readthedocs.io/en/latest/api.html)

[Discord Developer Portal ](https://discord.com/developers/applications)