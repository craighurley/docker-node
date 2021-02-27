# node

![build](https://github.com/craighurley/docker-node/workflows/build/badge.svg)

Run `node`/`npm` in a container.

## Running

```sh
docker run --rm -it -v $PWD:/workdir -w /workdir craighurley/node node
docker run --rm -it -v $PWD:/workdir -w /workdir craighurley/node npm
```

Optional: create an alias for the containers:

```sh
alias node='docker run --rm -it -v $PWD:/workdir -w /workdir craighurley/node node'
alias npm='docker run --rm -it -v $PWD:/workdir -w /workdir craighurley/node npm'
```
