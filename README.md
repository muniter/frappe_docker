| Develop | [![Build Status](https://travis-ci.com/frappe/frappe_docker.svg?branch=master)](https://travis-ci.com/frappe/frappe_docker)  |
|---------|-----------------------------------------------------------------------------------------------------------------------------|
| Master  | [![Build Status](https://travis-ci.com/frappe/frappe_docker.svg?branch=develop)](https://travis-ci.com/frappe/frappe_docker) |


## Getting Started

## Setting up Pre-requisites

This repository requires Docker, docker-compose and Git to be setup on the instance to be used.

For Docker basics and best practices. Refer Docker [documentation](http://docs.docker.com).

### Cloning the repository and preliminary steps

Clone this repository somewhere in your system:

```sh
git clone https://github.com/frappe/frappe_docker.git
cd frappe_docker
```

## Production Setup

It takes care of the following:

* Setting up the desired version of Frappe/ERPNext.
* Setting up all the system requirements: eg. MariaDB, Node, Redis.
* Configure networking for remote access and setting up LetsEncrypt.

1. Single Server Installs
    1. [Single bench](docs/single-bench.md). Easiest Install!
    2. [Multi bench](docs/multi-bench.md)
2. Multi Server Installs
    1. [Docker Swarm](docs/docker-swarm.md)
    2. [Kubernetes](https://helm.erpnext.com)
3. [Site Operations](docs/site-operations.md)
4. [Custom apps for production](docs/custom-apps-for-production.md)
5. [Tips for moving deployments](docs/tips-for-moving-deployments.md)

## Development Setup

It takes care of complete setup to develop with Frappe/ERPNext and Bench, Including the following features:

- VSCode containers integration
- VSCode Python debugger
- Pre-configured Docker containers for an easy start

[Start development](development).

## Contributing

- [Frappe Docker Images](CONTRIBUTING)
- [Frappe Framework](https://github.com/frappe/frappe#contributing)
- [ERPNext](https://github.com/frappe/erpnext#contributing)
- [frappe/bench](https://github.com/frappe/bench)