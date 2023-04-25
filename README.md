# Docker

## What is docker?

1. Docker is a tool for running applications in an isolated environment.
2. It's an application system which gives us the facilities of container-based operating system level virtualization.
3. Docker is an implementation of the concept of operating system level virtualization.

## What is operating system level virtualization?

1. Operating system level virtualization is the existence of more than one isolated user space on a kernel.

## What is docker container ?

1. Docker container provides us runtime, system tools, system library, etc.
2. Each docker container is a minimal Linux server.
3. Containers are the separated isolated user spaces on a kernel.
4. A container is very lightweight and it uses very minimal hardware resources, less than a virtual machine.
5. Main facilities of containers are microservice architecture, application scaling, and painless deployment.

## What is docker image ?

1. Docker image is a composed system which comes with all application software and its dependencies for a virtual environment.
2. A docker container image is a lightweight, stand-alone, executable package of a piece of software that includes everything needed to run it: code, runtime, system tools, system libraries and settings.
3. A container image is a shareable snapshot of a container.

### Docker options, management commands & commands:

```bash
$docker
```

or,

```bash
$docker --help
```

### Docker version:

```bash
$docker version
```

or,

```bash
$docker --version
```

or,

```bash
$docker -v
```

### Docker info: info like number of running, paused & stopped containers etc.

```bash
$docker info
```
