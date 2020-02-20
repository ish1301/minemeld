# MineMeld

Docker deployment with Docker Swarm

    git clone git@github.com:ish1301/minemeld.git
    cd minemeld
    docker swarm init
    docker stack deploy -c docker-compose.yml minemeld

You have minemeld running at https://localhost:6060 using official docker image at `https://hub.docker.com/r/paloaltonetworks/minemeld`
