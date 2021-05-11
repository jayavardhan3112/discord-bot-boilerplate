# discord-bot-boilerplate

Starting point for creating python based Discord Bot

## Requirements
You need Python 3.4 or later to run discord-bot-boilerplate.
Recommend using Python 3.6+
Python packages are available at http://www.python.org/getit/

## Running the tests

[Discord Developer portal]https://discord.com/developers/applications
- Click on new application and set a name for you bot
- page will be redirected -> go to the bot section and click Add Bot
- Copy the bot Token (It should be a secret)
- Invite the boot to our server -> 
    - for this go to the Oauth2 section 
    - go to the scopes section
    - select the scope as Bot
    - add the permissions for the bot
    - be careful about the Admit permission (not required)
    - A url is generated whiich you can copy and paste it in a new tab
    - it asks for the server to be added to
    - you have to allow the permissions
    - Hurray!! the bot has joined the server 

You can use Replit to host your code on cloud for free

To Run:
```
$ virtualenv venv --python=python3
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python app.py
```

## Built With

* [Discord.py](https://github.com/Rapptz/discord.py) - Discord python3 API wrapper

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
