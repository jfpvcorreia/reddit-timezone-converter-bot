# Running the bot in Docker

## Update env file with your credentials

update and rename .env.example to .env

## Build docker image

From the root of the project, run this docker build command: `docker build -t reddit_timezone_converter_bot:latest . --no-cache`

## Run Docker Image

`docker run -d --name=reddit-timezone-converter-bot reddit_timezone_converter_bot:latest`

## View Logs

`docker logs -f reddit-timezone-converter-bot`
