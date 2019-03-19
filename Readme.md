# REVAMP Employee Frontend Project

## Contains

- [x] [Typescript](https://www.typescriptlang.org/) 3
- [x] [Angular](https://github.com/angular) 7
- [x] [Docker]
- [x] [Docker-compose]

## Installation & Running

```
$ docker-compose up
```
Check project at port `4100`
=========================

## DOCKER DOCUMENT
> This project was combined by docker-compose. It has 2 main parts: Mongodb and express-server (port 3000). With docker-compose, they can run together by only some command lines.
> You need to check the `.env` files. Try to create if it is not exist with `.env.sample` file.
> After We need to build the images and containers first
```
docker-compose build
```
> After we can run the project by
```
docker-compose up
```
> More command line we need to view
```
docker-compose down `kill container`
docker-compose stop `just stop container`
docker rmi `remove images`
docker rm `remove container`
docker ps `show all containers are running`
docker ps -a `show all containers were stopped`
docker images `show all images`
```
=========================

# License

MIT
