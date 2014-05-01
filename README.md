# leiningen-docker

Dockerfile for running [Leiningen](https://github.com/technomancy/leiningen).

## Usage

1. Build the image:

    `docker build -t alexguev/leiningen .`

2. Run repl:

    `docker run -i -t alexguev/leiningen lein repl`
