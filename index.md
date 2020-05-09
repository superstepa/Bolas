# Bolas

Bolas is a mtg card-fetcher discord bot that is heavily inspired by [yawgmoth](https://github.com/Lerker3/yawgmoth).
## How to run

Export BOLAS_SECRET_TOKEN. Execute run.py.

```sh
#!/usr/bin/env bash
export BOLASDIR=/home/bolas/bolas
export $BOLAS_SECRET_TOKEN=THIS-IS-A-SECRET

cd $BOLASDIR
source $BOLASDIR/bin/activate
pgrep -f run.py || python $BOLASDIR/run.py

```

## Stats

Fetching cards for 371 servers and 69618 users (38092 unique users) as of May 2020.

## Add Bolas to your Discord server

[Click here](https://discordapp.com/oauth2/authorize?client_id=245372541915365377&scope=bot&permissions=0)
