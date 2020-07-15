# remote-php-docker

## app

```
$ docker-compose exec app /bin/sh

php -v
```

## web check

```
$ mkdir src/public
$ echo "Hello World" > src/public/index.html
$ echo "<?php phpinfo();" > src/public/phpinfo.php
```

after checking

```
$ rm -rf src/*
```