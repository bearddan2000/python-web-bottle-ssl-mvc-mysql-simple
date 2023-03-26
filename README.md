# python-web-bottle-ssl-mvc-mysql-simple

## Description
Simple web app that serves a static web page
for a bottle project.

Uses sqlalchemy query a table `dog`.

Is self-signed ssl cert.

## Tech stack
- python
  - bottle
  - sqlalchemy
  - cheroot
  - beaker
- bootstrap
- jquery
- dataTable
- mariadb
- ssl

## Docker stack
- alpine:edge
- python:latest
- mariadb:latest

## To run
`sudo ./install.sh -u`
- [Availble at](https://localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
