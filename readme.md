# GravityGuard Bot 
## Table of Contents
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Configuration](#configuration)
  - [Commands](#commands)
  - [Support](#support)
  - [Contact](#contact)
  - [License](#license)

## Introduction

GravityGuard Bot is designed to improve your Discord server with a variety of engaging features, such as music playing, helpful commands, and more. This bot is a general-purpose bot for enhancing the server experience while leaving server moderation to the **GravityGuard Bot**.

## Features

- Automated welcome messages for new members.
- Rules posting and management.
- Help command to guide users with available bot commands.
- Echo command to repeat user input.
- Music playing with `yt-dlp` on a designated **music channel**.
- `!ping` to check the bot's response time to Discord.

## Installation

To set up the DarkDeity Discord Bot on your server, follow these steps:

1. Clone the repository:

    ```bash
    https://github.com/zeroaxiis/GravityGuard.git
    ```

2. Navigate to the project directory:
 
    ```bash
    cd GravityGard-Bot
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables for your Discord bot token. You can either use `.env` or set them manually:

    ```bash
    export DISCORD_TOKEN='your_discord_bot_token'
    ```

## Usage

To start the bot, run:

```bash
python bot.py
```

## Configuration

You can configure the bot using a `config.json` file located in the root directory. This file includes settings like welcome messages, rule texts, and more.

Example `config.json`:

```json
{
  "welcome_channel": "welcome",
  "rules_channel": "rules",
  "help_command": "!help",
  "prefix": "!"
}
```

## Commands

Here is a list of available commands:

- `!welcome`: Sends a welcome message to the designated channel.
- `!rules`: Posts the server rules.
- `!help`: Displays the help message with a list of available commands.
- `!echo [message]`: Repeats the message back to the channel.
- `!hello`: Greets the user.
- `!support`: Provides support contact information.
- `!contact`: Displays contact information for the server admin.
- `!info`: Provides information about the server.
- `!ping`: Checks the bot's response time to Discord.
- `!clear [number]`: Deletes a specified number of messages from a channel.
- `!music [song name]`: Plays a song in the **music** channel (uses `yt-dlp` for audio playback).

## Support

If you encounter any issues or have questions, please create an issue on the [GitHub repository](https://github.com/zeroaxiis/GravityGuard.git/issues) or reach out for support.

## Contact

Created by [Ashish Chaurasiya](https://github.com/DrDead0).

## License

This project is licensed under the MIT License - [To See The LICENSE Click Here](https://github.com/zeroaxiis/GravityGuard?tab=GPL-3.0-1-ov-file)
