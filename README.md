# Free DarkOrbit Pixel Bot

This script makes your spaceship navigate randomly over any DarkOrbit map.
It will manage your PET, repair your ship, reconnect after disconnects and more.
Take a look at the features and roadmap section to see what this free and opensource bot can do.

## PinkGalaxy XDream

The current `DO-PIXEL-BOT.js` copy defaults to PinkGalaxy launch mode. Run it in Botfather with the complete `templates` directory beside the script. It opens PinkGalaxy, waits for manual sign-in and CAPTCHA completion, then waits for **START > XDream Client > Stable**. It clicks the XDream **START** button and stops after detecting the in-game minimap.

Gameplay automation is intentionally paused: the existing DarkOrbit navigation, loot, repair, reconnect, ship, and PET recognition has not been calibrated for PinkGalaxy. The XDream power icon exits the game and is not used as a ship stop control.

For Botfather, download and extract the [complete PinkGalaxy package](./PGBOT-PinkGalaxy-1.2.1.zip). Keep the extracted `templates` directory beside `DO-PIXEL-BOT.js`.

## How to run this bot script?

- Download this repository and extract it
- Edit the Botfather configuration and keep the `templates` directory beside `DO-PIXEL-BOT.js`
- Use the [botfather.io client](https://botfather.io/downloads) to run the bot script

[Step by step tutorial](https://pbdo-bot.net/tutorial.html)

## Features and Roadmap:

[x] Full Background Mode (integrated browser)
[x] Automatic Login
[x] Automatic Reconnect
[x] Automatic Ship Repair
[x] Adjustable max. Ship Repairs
[x] Fly back to Map after Death
[x] Random Map Navigation
[x] Automatic PET Repair
[x] Automatic PET Gear Selection
[ ] Automatic Cloak CPU activation
[x] Automatic Bonus Box collection
[ ] Automatic Pirate Booty collection
[ ] Automatical flee on low HP
[ ] Automatic NPC Shooting on lower maps