# node

![build](https://github.com/craighurley/docker-node/workflows/build/badge.svg)

Run `node`/`npm` in a container.

## Running

```sh
docker run --rm -it -v $PWD:/workdir craighurley/node
docker run --rm -it -v $PWD:/workdir --entrypoint=npm craighurley/node
```

Optional: create an alias for the containers:

```sh
alias node='docker run --rm -it -v $PWD:/workdir craighurley/node'
alias npm='docker run --rm -it -v $PWD:/workdir --entrypoint=npm craighurley/node'
```
