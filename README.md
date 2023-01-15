<!-- PROJECT LOGO -->
<br />
<p align="center">
    <h3 align="center">Map History Bot</h3>
    <p align="center">
        A Simple Discord / A2S Bot
    </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

<!-- ABOUT THE PROJECT -->

## About The Project

This is a simple implementation of a discord bot using A2S to query Source (Steam) Game-Servers for Maps.

### Built With

- [Discord.py](https://github.com/Rapptz/discord.py)
- [Python A2S](https://github.com/Yepoleb/python-a2s)

<!-- GETTING STARTED -->

## Getting Started

1.  Clone the project
2.  Edit your `configuration.json`
3.  launch `main.py`

### Prerequisites

You'll need the following packages and `Python 3.9.7` in order to run the bot:

- discord.py

```sh
pip3 install discord.py
```

- python-a2s

```sh
pip3 install python-a2s
```
- jaraco.docker
```sh
pip3 install jaraco.docker
```
### Installation

1. Get a discord Bot free Token at [Discord Developer Portal](https://discord.com/developers/applications), you can follow [this guide](https://discordpy.readthedocs.io/en/stable/discord.html) by the [Discord.py](https://github.com/Rapptz/discord.py) team
2. Clone the repo and create a `configuration.json`

```sh
gh repo clone QwertzeZ/maphistory-bot-main---Kopie
```
```json
{
    "TOKEN": "",
    "PREFIX": "!",
    "SERVER": {
        "IP": "",
        "PORT": 27165
    },
    "INTERVAL": 600.0
}
```

3. Install all the required packages

```sh
pip3 install -r requirements.txt
```

4. Enter your Token in `configuration.json`

```JSON
"TOKEN": "your token here",
```

5. Enter your Server IP and PORT in `configuration.json`

```JSON
    "SERVER": {
        "IP": "194.26.183.182",
        "PORT": 27165
    }
```

6. Invite the Bot to your discord via the [Discord Developer Portal](https://discord.com/developers/applications)
7. Profit 💯

<!-- USAGE EXAMPLES -->

## Usage

use `!history` or `!maps` on your discord in order to display the last 10 Maps

<!-- ROADMAP -->

<!-- CONTRIBUTING -->

<!-- CONTACT -->