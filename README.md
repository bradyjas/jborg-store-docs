# Project Documentation for store.jasonbrady.org

This repository contains the Markdown documentation files for the demostration
e-commerce website [store.jasonbrady.org](https://store.jasonbrady.org).

## Running `mkdocs` locally for development/test

You can start a container on your local system that runs `mkdocs` with the
`mkdir-materal` theme for development and testing purposes. First, start the
container:

```shell
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

Then open a web browser to the following URL:
[http://localhost:8000](http://localhost:8000)
