# node

![build](https://github.com/craighurley/docker-node/workflows/build/badge.svg)

Run `node`/`npm` in a container.

## Running

`node`

```sh
docker run --rm -it -v $PWD:/workdir craighurley/node
```

`npm`

```sh
docker run --rm -it -v $PWD:/workdir --entrypoint=npm craighurley/node
```

Optional: create an aliases for the containers:

```sh
alias node='docker run --rm -it -v $PWD:/workdir craighurley/node'
alias npm='docker run --rm -it -v $PWD:/workdir --entrypoint=npm craighurley/node'
```
