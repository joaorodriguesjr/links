Initially inspired by the simplicity of the linktree service this project is kind of a portfólio page with focus on important links to expose some things that I do as a software developer.

It is written with basic web technologies (HTML5, CSS3) but it has some extra spice on the development and production environments, both running on containers.

For the development environment the project runs on a Node JS server with auto reloading via Docker. The production server is a Nginx container deployed by a Github workflow running on a single node Kubernetes in the cloud.

## Development Environment

```shell
docker-compose --file docker/compose.yml --project-name links up
```

## Production Environment

![Kubernetes Deployment](https://github.com/joaorodriguesjr/links/actions/workflows/deployment.yml/badge.svg)

https://joaorodriguesjr.com
