# docker-web-druid-postgres

## Description
Uses apache druid to capture data from postgres.

## Tech stack
- postgres
- druid
  - zookeeper

## Docker stack
- postgres:latest
- apache/druid:27.0.0

## To run
`sudo ./install.sh -u`
- [Avalble](http://localhost:8081)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Druid quick start](https://github.com/apache/druid/tree/27.0.0/distribution/docker)