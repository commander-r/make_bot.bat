# make_bot.bat
This will create a simple &amp; working discord.js V13 (with slash commands) discord bot with only one file!

* * *

<h1>You will need to remove all the " at the start and end of every .js file!</h1>
<br>
Hello, and thank you for choosing my (base) code for your project!<br><br><br>
<h2>What this code will do:</h2><br>
<pre><code>md bot && cd bot
md events && cd events</code></pre>
This (^^) code will create 2 folders, 1 folder named bot (the main folder where everything is going to be inside of.), and 1 folder named events (this is where all the events files (that will be created a bit later) will be made in). and goes inside of those folders.<br> <br><br>
<h2>What this code will do:</h2>
<br>
<pre><code>echo "SOME_CODE_HERE" > interactionCreate.js
echo "SOME_MORE_HERE" > ready.js && cd ../
</code></pre>
This (^^) code will create 2 files, 1 file named interactionCreate.js (This file is needed for every slash command that will be done), and 1 file named ready.js (This file is for the statuschanging of the bot). and goes back to the main folder.<br> <br><br>
<h2>What this code will do:</h2>
<br>
<pre><code>md commands && cd commands
md utility
</code></pre>
This (^^) code will create 2 folders, 1 folder named commands (In this folder there will be other folders and in those will be the actual commands), and 1 folder named utility. and goes back to the main folder.
<br>
After it did this, the bot will make a file (named ping.js) in the utility folder like this:<br>
<pre><code>echo "PING_COMMAND_CODE_IN_HERE" > ./utility/ping.js && cd ../</code></pre><br><br><br>
Now when it did that, i will return to the main folder (bot) and create a new file named "config.json" like this:
<pre><code>echo CONFIG_CODE_HERE > config.json
</code></pre>
This is the only file that you'll need to fill in stuff. The stuff you need to fill in are the token, clientId, testGuildId and the channelId's. To get the token and ClientId <a href="https://canary.discord.com/developers" title="discord.com/developers">Head over to this website</a> and create an application. Go to bot and press the "copy token" button. <br> <br><br>
After this it will create 2 more files in the main folder (bot), and those are the index, main, and deploy-commands.js.
