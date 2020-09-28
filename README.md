<a href="https://fontmeme.com/discord-logo-font/"><img src="https://fontmeme.com/permalink/200928/23f4ca32638ebf256b80162c1bc727ad.png" alt="discord-logo-font" border="0"></a>
<a href="https://fontmeme.com/discord-logo-font/"><img src="https://fontmeme.com/permalink/200928/48d6f42dbe9624198e085a6b8876b534.png" alt="discord-logo-font" border="0"></a>

[![Discord Server Badge](https://img.shields.io/discord/745447009242316860?color=7289DA&label=Discord%20Server&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/GuBufUE)![Programming Language](https://img.shields.io/badge/-Java-orange?style=flat-square&logo=java)

Discord Guild Greeter is a Discord Bot Module written in Java using the Javacord API which allows inexperienced developers to create a good quality greeting bot. It takes in up to 9 variables, some of which can be left blank.
For other projects, see [here](https://github.com/asciitac)

# Setup
Go to ``/discordGuildGreeter/src/main/java/configuration.java`` and set the given variables to your choosing. 

``String`` ``TOKEN`` is your Discord Bot Token. This should be kept secret and can alternatively be an environment variable. You should not share this with anyone, as it gives them complete access to your Discord Account! You can get your bot token from ``https://discord.com/developers/applications/<YOUR PROJECT ID HERE>/bot``.

``Boolean`` ``sendPrivateMessage`` dictates if they recieve a direct message. 

``String`` ``privateMessage`` is that direct message.

``Boolean`` ``isPrivateMessageEmbed`` dictates if the direct message comes in the form of an ``Embed``.

``Color`` ``privateMessageColor`` is the colour of that ``Embed``.

``Boolean`` ``sendChannelMessage`` dictates if the alert is sent to a ``serverTextChannel`` in a ``Server``

``String`` ``channelID`` is the ID of the ``serverTextChannel`` that the alert will be sent to.

``String`` ``channelMessage`` is the message that is sent to the ``serverTextChannel``

``Boolean`` ``isChannelMessageEmbed`` dictates if the message comes in the form of an ``Embed``.

``Color`` ``channelMessageColor`` is the colour of that ``Embed``.

Run ``/discordGuildGreeter/src/main/java/runMe.java`` to start the bot.

# Additional Notes
Skidding, the act of copying one's work without giving due credit, is highly advised against. I ask that you provide me credit wherever this is used. You can mention either @asciitac or @gigitac.
