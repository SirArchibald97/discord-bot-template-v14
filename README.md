# Discord Bot Template
This is a simple boilerplate template to be used to easily create Discord bots using Discord.js v14. Feel free to use this however you want!
See below for the simple installation steps.

### Installation
1. Create a repo using this template and clone it to your machine
2. Open a terminal window in that location and run the command `npm install` to install the neccessary packages
3. Create a new file named `.env` and add two values as shown below
   
   ```env
   # your application's token, do NOT share this with anyone
   # this can be found by heading to your application's bot page in the discord developer portal and clicking "reset token"
   # you can then copy and paste the value here
   TOKEN=ABCDEFGHIJKLMNOPQRSTUVWXZY
   
   # the ID of the server you are registering the commands in
   # turn on developer mode in your discord client if you haven't already, and right click your server and press "Copy ID"
   GUILD_ID=123456789
   ```
5. Use `node index.js` or `node .` to run the bot

And it's as easy as that!
