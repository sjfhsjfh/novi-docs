# Welcome to Novi Documentation

## Local Deployment

Make sure you have installed [rye](https://rye-up.com/guide/installation/#installing-rye) and [Docker](https://docs.docker.com/get-docker/) first.

Clone the [`novi`](https://github.com/project-novi/novi) project, navigate to the project folder, and start the service with the following commands:

```bash
rye build -a
docker build -t novi .
```
