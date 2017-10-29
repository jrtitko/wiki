# JR's assorted notes

## Building the Docker image
[Gollum Dockerfile](gollum-dockerfile)

```
docker build -t gollum .
```

## Starting this up
```
docker run -it -p 4567:4567 -v `pwd`:/gollum gollum
docker run -d -p 4567:4567 -v `pwd`:/gollum gollum

```