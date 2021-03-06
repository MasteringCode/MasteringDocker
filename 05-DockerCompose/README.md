# Docker Compose

## Intro

Compose is a tool for defining and running multi-container Docker applications. 
With Compose, you use a YAML file to configure your application’s services.
Then, with a single command, you create and start all the services from your configuration.

Using Compose is basically a three-step process:

1. Define your app’s environment with a Dockerfile so it can be reproduced anywhere.

2. Define the services that make up your app in `docker-compose.yml` so they can be run together in an isolated environment.

3. Run `docker-compose up` and Compose starts and runs your entire app.


### Useful links

- [https://docs.docker.com/compose/](https://docs.docker.com/compose/)
- [https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/)

---

# Next Section

- Exercise 01: [Running multiple containers](./Ex-01.md)
- Next section: introduction to [Development in Containers](../06-DevContainer)
