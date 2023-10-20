# jupyter-example-proxy

## Jupyter proxy

Proxy extension that provides Icon and starting instructions for you web application:

```
src/jupyter_example_proxy
```

## Web application

This package is using our example web application (https://github.com/huntdatacenter/workbench-app-example),
replace our example with your application.

## Development

Show quick help

```bash
make help
```

### Docker

Quick run locally with docker:

```bash
make rebuild
```

### Install from repository

If you need to install directly from repository for development / testing purposes:


```bash
python3 -m pip install git+https://github.com/huntdatacenter/jupyter-example-proxy.git@main#egg=jupyter-example-proxy
```
