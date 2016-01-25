# Dockerfile for jupyter

## How to use it?

```
$ docker pull satoshun/jupyter
$ docker run --rm -it -p 8888:8888 -v "$HOME/notebooks:/notebooks" satoshun/jupyter
```

`$HOME/notebooks` is your notebook direcotry of local.


## Specs

- Ubuntu 15.10
- Python3.4
