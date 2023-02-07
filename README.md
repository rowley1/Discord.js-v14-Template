# Introduction

Hello! I am Shaurya Bansal. I live in India. I am a programmer and a web developer. Feel free to use my djs template to get a head start. `My Discord tag - fin#6856`

# Discord.js v14 Template

A basic Discord.js v14 template to get your started.

## Startup

- Create a file named `.env`.
- An example has been created `example.env`.
- Enter the following details to it:

```
TOKEN=YOUR TOKEN
MONGODBURL=YOUR MONGODB URL [Only required for commands which requires some data to store]
```

- Save the file.
- Go to `config.json` and enter the following details to it:
```
{
  "global": true,
  "delete_commands": false,
  "dev_guild_id": "1059888290104348792",
  "dev_id": ["657592248224972811"],
  "client_id": "1067822298641473556",
  "error_channel_id": "1037603640506056704"
}
```
- Set `global` true if you want the commands to be in all the guilds and set it to false if you want the commands to be just in a single guild i.e. `dev_guild_id`.
- Set `delete_commands` as true only when you want to delete all you commands from a single guild or globally.
- Set `dev_guild_id` as your developer server's id.
- `dev_id` is an array. Provide all the ids of your bot devs. NOTE: THE DEVS HAVE ACCESS TO EVAL COMMANDS.
- Set `client_id` as your bot's id.
- Set `error_channel_id` as the id of the channel where you want the error logs of your bot.
- Open Terminal in the Project Directory.
- Run:

```
npm install
``` 
and then
```
node index.js or npm run dev or node .
```

## Configuration

- You can change your default embed color by changing

```
client.color="Your Color";
```

in `./index.js` line 45.

- You can change your default footer by changing

```
client.footer="Your footer";
```

in `./index.js` line 48.

## Template's Features

- Extremely comfortable handler. Very easy to use.
- Has Cooldown features
- Supports Slash Commands
- Awesome Console
- Error Handler
- Mention Reply
- Join Message
- devOnly commands
- maintanence commands
- userPerms
- botPerms
- eslint

## Next Version's Features

- I am going to add a ton of features in the next version like
- Automatic cooldown delete
- and much more. So stay tuned!

## Suggested Extentions for VSC

- Prettier ESLint
- ESLint
- Discord Rich Presence

## Credits

- FiredragonPlayz#0087
- Elitex#0007

# Thank you for using the template. Don't forget to star this repo!

In case of any bug, please open a pull request.
