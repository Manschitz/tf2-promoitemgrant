# Promotional Item Granting Utility for Team Fortress 2

## Disclaimer

The "Promotional Item Granting Utility" software has been created as Freeware for personal use by a Team Fortress 2 community contributor and it is not affiliated with or endorsed by [Valve Corporation](https://www.valvesoftware.com/) in any way.

For more information please refer to the "End-User License Agreement (EULA)" in the [LICENSE.md](https://github.com/Manschitz/tf2-promoitemgrant/blob/release/LICENSE.md) file.

Valve, the Valve logo, Steam, the Steam logo, Team Fortress and the Team Fortress logo are trademarks and/or registered trademarks of [Valve Corporation](https://www.valvesoftware.com/).

## Description

Main purpose of the "Promotional Item Granting Utility" is to provide a graphical user interface for distributing promotional items (e.g. badges or medals) in Team Fortress 2 by utilizing the [Steam Web API](https://steamcommunity.com/dev). It may be used by hosts of Team Fortress 2 community events (e.g. tournaments, contests and competitions) who have been given permission and access to distribute promotional items by [Valve Corporation](https://www.valvesoftware.com/).

## Features

- Look up any Steam user by a given Steam profile URL or SteamID64
- Import a list of Steam user profile URLs or IDs from a text file to distribute items to
- Distribute Team Fortress 2 promotional items to Steam users through the [Steam Web API](https://steamcommunity.com/dev)
- Logging of all actions and errors to a file
- Tracking of given items in a CSV file to prevent distribution of multiple items to users

## Possible future features

- Check a user's inventory directly through the [Steam Web API](https://steamcommunity.com/dev) for any existing items of the given type to prevent distributing duplicate items (instead of using a CSV file to track given items)
- Make all requests asynchronous to improve UI responsiveness
- Add manual cancelation to the item granting process so it can be stopped in case you'd like to pause or cancel while the distribution process is already running
- Add check on startup for any available updates to the Software

## Quick Start Guide

- Download the [latest installer](https://github.com/Manschitz/tf2-promoitemgrant/raw/release/Promoitemgrant_1.0_Setup.exe) and extract the files to your computer
- Enter your Steam Web API key under the "Settings" tab (get one from Steam at [https://steamcommunity.com/dev/apikey](https://steamcommunity.com/dev/apikey))
- Either look up a single user profile or import a list of users from a text file (use only one profile URL or ID per line)
- Enter the item's promo ID that was given to you by Valve
- Click "Grant item to users..." to start the distribution process (this may take a few moments as a single request will be sent to the Steam Web API for each user)
- Take a look at the [Wiki](https://github.com/manschitz/tf2-promoitemgrant/wiki) for more information

## Personal notes from the developer

If you have feedback or questions that are not answered in the [Wiki](https://github.com/manschitz/tf2-promoitemgrant/wiki) send me a message on [Steam](http://steamcommunity.com/profiles/76561197988875517/) or an email at [contact@manschitz.com](mailto:contact@manschitz.com).

This tool will always be Freeware and you're under no obligation to pay for it. However, if you'd like to support my work, I greatly do appreciate any donations you send me through PayPal at [https://www.paypal.me/workdonations](https://www.paypal.me/workdonations).

