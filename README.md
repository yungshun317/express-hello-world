# Express Hello World

[![Made with JavaScript](https://img.shields.io/badge/Made_with-JavaScript-pink.svg)](https://img.shields.io/badge/Made_with-JavaScript-pink.svg) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project demonstrates a simple Express server running in a Docker container.

## Up & Running

The server can be run with:
```
~$ npm run start
```
Then go to `localhost:8080`.

Or run with Docker:
```
~$ docker build -t express-hello-world .
~$ docker run -d -p 8080:8080 --name express-hello-world express-hello-world
```
Also open with `localhost:8080`.

## Features

This project mainly contains two parts:
- Dockerfile.
- Express Hello World application.

## License
[Express Hello World](https://github.com/yungshun317/express-hello-world) is released under the [MIT License](https://opensource.org/licenses/MIT) by [yungshun317](https://github.com/yungshun317).
