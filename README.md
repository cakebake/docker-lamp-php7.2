Docker LAMP
===========

incl. Ioncube Loader & xDebug

Features

-	PHP 5.6
-	ionCube PHP Loader
-	Zend OPcache
-	Xdebug
-	Composer
-	MySQL

Web access: http://localhost:8080/

Build
-----

```
docker-compose build
```

Run
---

```
docker-compose up
```

or

```
docker-compose up -d
```

> Param `-d` runs container in background (detach)

Bash into
---------

```
docker exec -ti php56 /bin/bash
```

> Container name is `php56`

Stop
----

```
docker-compose down
```

> To stop all containers and kill all volumes `docker-compose down --volumes`. Data (mysql databases, ...) will be lost!
