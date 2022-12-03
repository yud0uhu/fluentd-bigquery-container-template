# fluentd-bigquery-container-template

## make docker image

```sh
$ docker build -t fluentd-bigquery .
```

## run docker container

```sh
$ docker run --rm -it -p 24224:24224/tcp -p 5140:5140/tcp fluentd-bigquery:latest
```

## using docker image

https://hub.docker.com/r/fluent/fluentd/

## using plugin etc.

https://github.com/fluent-plugins-nursery/fluent-plugin-bigquery
