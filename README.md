# ecstatic

Ths is a minimal docker image that serves static using latest nginx on top of Alpine Linux.

## Prerequisites

- Docker.

## Usage

- Launch docker image detached.

`docker run -d --name <MY_SERVER_NAME> -p 80:80 -v </ABSOLUTE/PATH/TO/CONTENT/>:/var/html/www magandrez/ecstatic`

- Hit your browser at `localhost`.
