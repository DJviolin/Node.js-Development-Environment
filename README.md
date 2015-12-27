# Node.js Development Environment

## Prerequisites

1. Docker Client
2. Docker-compose

## Usage

Run docker-compose:

```
$ docker-compose --file ~/node/docker-compose.yml build
```

Running Node.js:

```
$ chmod +x ~/node/node
$ cd ~/node
$ ./node -v
$ ./node /root/node/hello-world.js
```

Running NPM:

```
$ chmod +x ~/node/npm
$ cd ~/node
$ ./npm -v
```

Place your project files in the `~/node/work` directory.

Have fun with your Dockerised Node.js development environment!
