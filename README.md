# [HogNuker](https://hognuker.herokuapp.com/)

HogNuker is a nuking tool for Discord. It should be able to run on any device. **If you find any errors, open an issue and include a screenshot of the error and steps to re-create it.** If you have any suggestions, feel free to file them under issues or [join the Discord server](https://pastebin.com/raw/DNVr7dGC).

# Usage Guide

https://hognuker.herokuapp.com/ is the official URL for HogNuker. Any other URLs are token loggers and probably IP loggers as well. When first opening HogNuker, you will be greeted with this screen. Click on "Settings" to be sent to the settings page.
![](/guide/nologin-home.png)
![](/guide/nologin-settings.png)

Create a bot and copy its token. Go to https://discord.com/developers/applications and click on the "New Application" button in the top-right corner.
![](/guide/discord-createapplication.png)

Once you create an application, navigate to the "Bot" tab on the sidebar.
![](/guide/discord-appoverview.png)

Click the "Add Bot" button and then click the button that says "Copy Token". Paste the token into the box in the settings page.
![](/guide/discord-botpage.png)

Once you create your bot, scroll down to the "Privileged Gateway Intents" section and enable make sure these sliders are checked.

### **These are necessary for the bot to receive commands.**

![](/guide/discord-intents.png)

Copy the token of your bot, paste it into the box, and click the "Connect" button.
![](/guide/discord-example1.png)

Once you are logged in, return to the home page. Click the checkbox that says "Administrator" and click the button that says "Copy OAuth2 URL".
![](/guide/login-home.png)

The link in your clipboard is what you and others will use to add the bot to servers. To add it, select a server from the drop-down menu and click "Continue". You may need to complete a captcha if it is your first time.
![](/guide/discord-addbot.png)

Once your bot has joined and you have the admin permissions, you can execute any commands you want. My personal favorite and suggested method is to execute the "Give Admin" command ($nadmin by default), execute the "Nuke" command ($nuke by default), and then cut the attack after the first 300-ping burst and launch the "Mass Ban" command ($nban by default).
![](/guide/commands.png)

# Have Fun!

![](/guide/Demo.gif)

# Icon by Kixxer

![](/favicon.png)
