<div align="center">
<img src="https://i.imgur.com/MkFud1l.png" align="center" alt="Logo" height="100">
<br>
<br>
<strong><i>An open-source discord bot for SA-MP(San Andreas Multiplayer) Servers/ Communities</i></strong>
<br>
<br>
<hr>
</div>

<br>

## Setting up the bot for free in Heroku. 📍
1. Clone this repository in your own Github account.<br />
1.1. Once you have the repo cloned you can edit a few functions such as unban and report sync seeing the examples given <br />
2. Create a free account in Heroku by [Clicking here](https://signup.heroku.com/)<br />
3. You will also need a Secret Bot Token to deploy this bot successfully. [Click here](https://www.writebots.com/discord-bot-token/) to see how to generate a bot token and invite your bot to your server.<br />
4. Create a new app and deploying in Heroku.<br />
4.1. Create a New App from the dashboard<br />![New APP](https://i.imgur.com/BZ1kFo9.png).<br />
4.2. Select the deployment method as Github and connect to your repository. ![](https://i.imgur.com/BbnmYwy.png)<br />
4.3. Once liked to the repo you either manually deploy the app or enable automatic deployments.<br />
4.4. Configure the Environment Variables by going to config vars in the settings tab. ![](https://i.imgur.com/CZU9YNv.png)<br />
4.5. To start the bot goto resources tab and turn off the web.js and turn on the bot.js. ![](https://i.imgur.com/z5WlYVB.png)<br />
5. Now you should see your bot online in your discord server

---
## Initial Setup. 📝
-After the bot is online, add a role for your bot with proper permissions(Admin Permission Recommended) .<br />
-Now setup the channels using the cmd /setchannel alternatively if you haven't set up the SAMP Ip and port in code, you can use /setip,/setport.<br />

---

## Alternate Method For Test Deployment📝 <br />(Not recommended, but can be used to test with limited functionality) 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

---

