# Tiny Python Docker image
The most lightweight python docker image possible

## Possible variants
| Dockerfile   | Idea | Size |
| :----------- | :--- | :--: |
| Dockerfile.alpine | Alpine-based | 49.2 MB |
| Dockerfile.ubuntu | Ubuntu-based | 112 MB |

## Building image
```bash
docker build -t tiny-python-docker-image . -f <Dockerfile name>
```
For example:
```bash
docker build -t tiny-python-docker-image . -f Dockerfile.ubuntu2004
```


## Running image
```bash
docker container run --rm -it tiny-python-docker-image
```