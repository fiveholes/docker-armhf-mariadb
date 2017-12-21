# docker-armhf-mariadb

This images contains an instance of mariadb, based on ALPINE, runnable on Odroid XU-4

GitHub repository [github.com/fiveholes/docker-armhf-mariadb](https://github.com/fiveholes/docker-armhf-mariadb)

## Docker Informations

* This image expose the following port

| Port           | Usage                    |
| -------------- | ------------------------ |
| 3306           | MariaDB applicative port |

* This image takes theses environnements variables as parameters

| Environment        | Usage           |
| -------------      | --------------- |

* The following volume is exposed by this image

| Volume         | Usage                          |
| -------------- | ------------------------------ |
| /var/lib/mysql | The database storage directory |

## Installation

* Manual (from an arm device)

```
git clone
docker build -t fiveholes/amrhf-mariadb .
```

* or Automatic

```
docker pull fiveholes/amrhf-mariadb
```


## Usage

```
docker run -p 3306:3306 fiveholes/amrhf-mariadb
```
