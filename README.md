# Globaleaks swarm

## installing

- Clone this repository

  `git clone https://github.com/transparency-finland/globaleaks-swarm`

- Initialize swarm (sudo if needed)

  `docker swarm init`

- inside the directory, run (sudo if needed) 

  `docker stack deploy --compose-file globaleaks-swarm.yml globaleaks`

## How to use

To monitor the swarm, visit `localhost:4040`

To manage the swarm, visit `localhost:9000`

To use globaleaks, visit `0.0.0.0`

To use globaleaks with tor, browse the url given by globaleaks
