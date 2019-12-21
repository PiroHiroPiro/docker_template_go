# Go Docker template

This is a Docker template that provides an environment with Go.

## Requirement

- [Docker](https://www.docker.com/)
  - docker-compose

## Usage

Run go:

```console
$ docker-compose run go bash
# go run echo.go
```

## Install

Clone repository:

```console
$ git clone https://github.com/PiroHiroPiro/docker_template_go.git
$ cd docker_template_go
```

Build images:

```console
$ docker-compose build
```

Initilaize Go module:
```console
$ cd source
$ go mod init
```

## Licence

This software is released under the MIT License, see [LICENSE](https://github.com/PiroHiroPiro/docker_template_go/blob/master/LICENSE).

## Author

[Hiroyuki Nishizawa](https://github.com/PiroHiroPiro)
