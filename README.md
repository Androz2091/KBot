# KBot

A discord bot for Kaizen. Uses Discord.js, Google-Spreadsheet and Node Js to track any cryptocurrency token from kalpha.fi

# Dependencies

You will need npm to run this program.

Use `npm i` to install dependencies (discord.js, google-spreadsheet).

**IMPORTANT : Add a config folder and a config.json file inside app like this app/config/config.json**

Add your Discord / API keys:

```json
{
    "CLIENT_ID": "REPLACE",
    "GUILD_ID": "REPLACE",
    "API_KEY": "REPLACE",
    "GOOGLE_API_KEY": "REPLACE"
}
```

# Start

Start the program with `npm start`. And then add the bot on your discord. It will now read and respond to messages.

# Commands

`!leaderboard` Displays info on top 5 KFarm cryptocurrencies based on APY

`!dApp:token` Displays info on a specific KFarm token. Example : !autofarm:usdt
