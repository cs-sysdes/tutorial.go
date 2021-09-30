# Tutorial: Golang in Workshop on System Design
This repository provides a base project to learn how to write Golang.

This lecture uses Go 1.17.
The lecture provides Docker container and will provide brief information on how to rely on it.

Using your own local development environment is also welcome, but this lecture will not describe how to set up it.
Even though you have Go development tools on your environment, Docker is still somewhat required because this lecture will use MySQL DB server later.

You can run the program with the following commands;
```sh
$ docker-compose up -d
$ docker-compose exec app go run main.go
```
Or, you can directly execute `go run main.go` if you have Go development tools.
