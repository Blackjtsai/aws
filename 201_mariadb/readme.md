201_mariadb
===============

```bash
$ docker pull mariadb:10.8
$ docker run --detach --name mariadb -p 3306:3306 --env MARIADB_USER=blackjtsai --env MARIADB_PASSWORD=eason821 --env MARIADB_ROOT_PASSWORD=eason821  mariadb:latest

```