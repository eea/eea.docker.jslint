# Docker image for JSLint checker

[JSLint](https://www.jslint.com/) is a static code analysis tool used in software development for checking if JavaScript source code complies with coding rules. 

## Supported tags and respective `Dockerfile` links

- [`latest` (*Dockerfile*)](https://github.com/eea/eea.docker.jslint/blob/master/Dockerfile)
- [`0.9.6` (*Dockerfile*)](https://github.com/eea/eea.docker.jslint/blob/0.9.6/Dockerfile)

## Usage

```console
$ docker run -it --rm -v /path/to/python/code:/code eeacms/jslint
```

## Advanced usage

```console
$ docker run -it --rm -v /path/to/python/code:/code eeacms/jslint --color /code/**/*.js
```

See `--help` for more options:

```console
$ docker run --rm eeacms/jslint --help
```
