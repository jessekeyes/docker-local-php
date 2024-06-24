# docker-local (simple PHP site) (Docker PHP-FPM 8.3 and Nginx)
### A local web dev environment
*based on this project: https://github.com/IshtarStar/docker-compose-nginx-phpfpm/*

- light weight simple docker container for quick flat web dev
- currently no db supported
- uses PHP 8.3

## Requirements

* docker
* docker-compose

### Optional but recommended

* degit `npm install -g degit`

## Steps

1. Set up a directory you want you project to live in.
1. From within that dir clone the github project: `jessekeyes/docker-local-php`, or with `degit`, run: `degit jessekeyes/docker-local-php myprojectdir`
1. This will create a project with this structure:
```
- myprojectdir

- - docker/
- - src/
- - .gitignore
- - docker-compose.yml
- - README.md

```

Create your project in the src/

