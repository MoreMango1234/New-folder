# Install Guide
## Prerequisites
[MongoDB](https://www.mongodb.com/)

[Node JS](https://nodejs.org)

## Installation

1. Clone this repo

    ```
    git clone https://github.com/TobiTenno/Zira.git
    ```
2. Run `npm i -g pm2` to install [PM2](http://pm2.keymetrics.io/)

3. Run `npm i` to install dependencies

4. Copy `pm2.example.json` to `pm2.json` and fill in the env variables

5. Run `git submodule init` and `git submodule update` to get the language files

6. Start the bot with `pm2 start pm2.json`


## Deploy your own!

You can deploy your own copy of Zira on heroku here:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/tobitenno/zira)
# affnitn
