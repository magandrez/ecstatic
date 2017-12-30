# ecstatic

Ths is a minimal docker image that serves static using latest nginx on top of Alpine Linux.

## Prerequisites

- Docker.

## Usage

`docker run -d --name <MY_SERVER_NAME> -p 80:8080 -v </ABSOLUTE/PATH/TO/CONTENT/>:/var/html/www magandrez/ecstatic`
