# kaizen-bot

For the Autodidactic Study Group Discord server.

## Dev env setup

Get the code + dependencies with `git clone --recurse-submodules https://github.com/omnisci3nce/kaizen-bot.git`

### Dependencies

`python3 -m pip install -U discord.py python-dotenv`

### Commands

`make dev` - runs docker-compose command to setup a PostgreSQL database and pgAdmin (admin UI for interacting with the database)

`make lint` - run this before pushing code. In the future, all code that makes it to master will need to pass lint + test phases
