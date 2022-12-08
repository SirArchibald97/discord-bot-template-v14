# Discord Bot Template
This is a simple boilerplate template to be used to easily create Discord bots using Discord.js v14. Feel free to use this however you want!
See below for the simple installation steps.

### Installation
1. Create a repo using this template and clone it to your machine
2. Open a terminal window in that location and run the command `npm install` to install the neccessary packages
3. Create a new file named `.env` and add the line ```TOKEN=[YOUR TOKEN]``` replacing `[YOUR TOKEN]` with your Discord application's token
   
   ```env
   TOKEN=ABCDEFGHIJKLMNOPQRSTUVWXZY
   ```
5. Open the `deploy.js` file and add your server ID to this line
   
   ```js
   - await rest.put(Routes.applicationGuildCommands(client.user.id, "GUILD ID HERE"), { body: commands });
   ↓
   + await rest.put(Routes.applicationGuildCommands(client.user.id, "918967225774391356"), { body: commands });
   ```
6. Use `node index.js` or `node .` to run the bot

And it's as easy as that!
