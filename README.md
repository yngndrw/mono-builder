Build [Mono runtime](http://www.mono-project.com/Main_Page) for use with the [Mono Heroku Buildpack](https://github.com/yngndrw/heroku-buildpack-mono).

To build:

```term
$ docker build -t my-user/mono-builder cedar-14/.
```

To build and upload new Mono version:

```term
$ docker run -v ${PWD}/cache:/var/cache -e VERSION=4.0.1 my-user/mono-builder
```
