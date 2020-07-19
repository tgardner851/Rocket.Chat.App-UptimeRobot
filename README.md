# Rocket.Chat.App-UptimeRobot

Register Webhooks for Uptime Robot notifications

## Docker
A Dockerfile and docker-compose are provided.

Build the docker image and run it to deploy to your server:
`docker build -t rocketchatapp_uptimerobot . && docker run -it --rm -e URL=YOUR_SERVER -e USERNAME=YOUR_USERNAME -e PASSWORD=YOUR_PASSWORD rocketchatapp_uptimerobot`

Build the docker image and run docker-compose to deploy to your server:
`docker build -t rocketchatapp_uptimerobot . && docker-compose run --rm -e URL=YOUR_SERVER -e USERNAME=YOUR_USERNAME -e PASSWORD=YOUR_PASSWORD rocketchatapp_uptimerobot`