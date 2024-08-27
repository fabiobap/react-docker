# React + Vite + Docker

## With Makefile:

Running for the first time:

`make first
`

from now on:

`make start`

---
## Without Makefile:

Running For the first time:

`docker compose up --build --no-recreate -d
`

From now on:

`docker compose up -d
`

To run npm commands first we need to enter into the container:

`docker exec -it vite_docker sh
`

running npm commands

`npm i && npm run dev`

---
thx to:
[https://dev.to/ysmnikhil/how-to-build-with-react-or-vue-with-vite-and-docker-1a3l](https://dev.to/ysmnikhil/how-to-build-with-react-or-vue-with-vite-and-docker-1a3l)
