# docker-deadman
Dockernized deadman container

## Run
```shell
# or 
docker pull kyokuheki/deadman
docker run --rm -it -v $PWD/deadman.conf:/deadman.conf kyokuheki/deadman
```

## Build
```sh
git clone https://github.com/kyokuheki/docker-deadman.git
docker build . -t deadman
```
