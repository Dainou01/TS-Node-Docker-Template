# TypeScript + NodeJS + Docker project template
Made by following [this blog post](https://dev.to/dariansampare/setting-up-docker-typescript-node-hot-reloading-code-changes-in-a-running-container-2b2f)

The project sets up a work environment where a running docker container autocompiles new TypeScript code into a dev environment. All deply tasks are automated through docker-compose and separeted into development and production.

## Dependencies
The project template requires the following to be installed:
- `node` and `npm`
- `docker` & `docker-compose`

Optionally, if you want to run docker-compose through the Makefile, you also need `make`.

## Using the template

First copy the project. You can do a simple 

```
git clone https://github.com/Dainou01/TS-Node-Docker-Template.git && rm -r TS-Node-Docker-Template/.git
```

