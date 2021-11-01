# Assemblyline
## ok

A webserver in a (tiny) docker container that returns 200 ok for every request on port 80, port 80 is not exposed, so this only works internally 


## Build Your Own

change `REPO` in the Makefile

```
make release
```

## Build Dependencies

* [Docker](http://www.docker.com/)
* [Go](https://golang.org/)
* make
