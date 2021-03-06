# Game Deals Discord Bot

[![BotLink](https://img.shields.io/badge/Discord-Invite%20bot%20to%20your%20server-blue?style=plastic&logo=discord)](https://discord.com/api/oauth2/authorize?client_id=773196224975077437&permissions=268445728&scope=bot)

## Description

This is yet another bot for Discord that tracks deals for games. Unlike the other ones that are available, this one operates differently.

The main priority in creating this bot was to minimize effort the user has to make. After inviting the bot to the server, it automatically creates required channels that are only available to it (so the other users can't send any messages there) and starts posting the deals there. But it doesn't mean, that there aren't any commands available!

It has it's own schedule, so everyday at the same hour (between 12:00 UTC and 13:00 UTC) it cleans the channels and posts new deals there. That way anyone who enters the channel will only see deals that are still available for purchase.

<p align="center">
  <img src=https://i.imgur.com/c7xNGn8.gif width="480" height="480">
</p>

Because Discord is somewhat of a limited frontend, the bot is also limited in amount of deals it can display. That's why it posts deals sorted by [Metacritic](https://www.metacritic.com) rating, so the user always sees the best possible deals.

### Built With
* [Python](https://www.python.org)
* [discord.py](https://pypi.org/project/discord.py)
* [aiohttp](https://pypi.org/project/aiohttp)
* [CheapShark API](https://apidocs.cheapshark.com)

## Examples

### Flip command
<img src=https://i.imgur.com/ZuYLZEl.gif width="480" height="326">

### Random command
<img src=https://i.imgur.com/mivYnRt.gif width="480" height="326">
