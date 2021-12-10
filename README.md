# ubuntu-docker-images

## Base Image
```
docker pull ubuntu
```

## ubuntu with zsh
i installed the zsh in the ubuntu base image.
```
docker pull xhq123/ubuntu-zsh
```

## ubuntu with zsh and conda
and then i installed conda in the image.
```
docker pull xhq123/ubuntu-conda
```

## ubuntu with zsh, conda and pipenv
and then i use `conda create` create python36 virtualenv and installed pipenv, and set some alias in `~/.zshrc`.
```
docker pull xhq123/ubuntu-pipenvpy36
```

## License
MIT

