# About
TBC (Trading Bots Commander) application was created in order to facilitate the process of managing trading bots. You can easily save and update the settings, create work profiles, start, stop and monitor your bots. TBC works with GBot trader terminal, all manuals and FAQ could be found on it's [official page](https://gbot-trader.herokuapp.com)

# Features
- Install and update GBot trader from user interface
- Easy to start - you don't need to install NodeJS or any NPM modules
- Create as many bots as you wish
- Create as many configs as you want
- Start, stop, switch between bot's configs with press of the button
- Monitor your bot's working process right in user interface
- Automatically start all active bots when app starts
- Mobile version of user interface

[Check out how-to video on YouTube](https://youtu.be/EiCj8JwZo8I)

# How to start
1. Get TBC from download section below and unzip it
2. To run TBC application:
    - On Windows run TBC-win.exe file
    - On MacOS open Terminal app, drag TBC-macos file to it and press Enter
    - On Linux run TBC-linux file from console
3. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000)
4. Install latest version of GBot trader from settings menu in TBC

# How to run bot
1. Create new bot in Bots column (left)
2. Create new working config for your bot in Bot configs column (middle)
3. In Config script column (right) paste your settings in KEY=VALUE format. Save your config
4. Activate selected config in Bot configs section (middle)
5. Perfect! Now you can start bot. Red indicator should become green

# Settings
All configs exists in JSON format. You can easily edit them, but before that read some information about syntaxis and other format details. It is also strongly adviced to use some advanced text editor with JSON syntaxis highlight to prevent any possible mistakes

*** app-default.json ***

| Parameters | Description | Type |
| --- | --- | --- |
| user | Username for TBC interface access authentication | string |
| pass | Password for TBC interface access authentication | string |
| verbUI | User interface debugging messages | boolean |
| dbName | App database name | string |
| bin | Bots file to run with TBC | string |
| cwd | Bots working directory | string |
| logSize | Number of messages from bot log to keep in memory | number |
| autoMon | Open bot monitor automatically on bot start/restart | boolean |
| checkBotUpdate | Time interval in hours to check GBot updates | number |
