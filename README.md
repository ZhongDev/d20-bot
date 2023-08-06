
# d20-bot
DiscordJS Dice Bot for Dungeons and Dragons

## :warning: Deprecated :warning:

This repository is no longer being worked on or supported and has been archived. The code and documentation in this repository are provided as-is, and no further updates or bug fixes will be made. Please use this repository for reference purposes only.

Commands
=====
*  ```!ping```: Pings bot<br>
*  ```!roll (dice notation)```: Roll a dice with dnd dice notation.

## Notation Examples
`!roll d4` will roll a 4 sided dice 1 time.<br>`!roll 2d6` will roll a 6 sided dice 2 times.<br>`!roll 2d20 d6 d10 d20` will roll a 6 sided dice 1 time, a 10 sided dice 1 time, and a 20 sided dice 3 times.

## Roll Examples
`!roll d4 d12 2d4` will result in a d4 roll, a d12 roll, then a 2d4 roll.
i.e.
`!roll d4 d12 2d4`
```
d4: (d4 roll)
d12: (d12 roll)
2d4: (2d4 roll)
```

### Note
`!roll` will only accept a dice side value of `4`,`6`,`8`,`10`,`12`,`20`, or `100`, and will only accept a dice quantity value of greater than or equal to `0`

Installation
=====
1) Clone this repository
2) Open a console in the `d20-bot` folder and run ```npm install```
3) Create a ```.env``` file inside the folder with ```TOKEN=(token)``` inside, replacing (token) your discord bot token.
4) To start, run ```node d20-bot.js``` or ```npm test```
