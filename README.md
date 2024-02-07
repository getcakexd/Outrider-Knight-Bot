About Outrider Knight
------------------
Welcome to Outrider Knight!

Outrider Knight is a simple Discord bot with basic features using slash commands.

However this bot doesn't support multiple server use.

Feel free to customize it to your needs.

Getting Started
------------------
1. Follow the official [discord.js guide](https://discordjs.guide) to create your bot.
2. Fill out all the information in the ``config.json`` and ``package.json`` files.
3. Clone this repository and run ``npm install`` in the direcotry of your project to download all the needed dependencies.
4. Start running your bot with the ``npm start`` command.
5. Finally run ``/help`` in your server to see all the commands.

Deployment
------------------
For deployment on cloud platform (e.g.: [Heroku](https://www.heroku.com)) make this change in the package.json file:

Before
```
  "scripts": {
    "start": "node deploy-commands.js && node index.js"
  },
```
After
```
  "scripts": {
    "build": "node deploy-commands.js",
    "start": "node index.js"
  },
```
Important:
- To deploy the bot successfully move the ``Procfile`` to the main directory.
- Due to the reddit api the ``/meme`` and ``/dankmeme`` commands don't work while the bot runs on a cloud platform.



Other Useful things
------------------

For auto start up on your local windows machine:
1. Press ``Windows key + R``
2. Type in ``shell:startup`` and hit ``enter``
3. Copy ``startup.bat`` into the folder
4. Open the file in notpad and change the directory path to lead to your project
5. Save the file and close it along with the File Explorer
   

For the official discord documentation click [here](https://discord.js.org/docs/packages/discord.js/14.14.1)

Check out Node.js [here](https://nodejs.org)
