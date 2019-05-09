# docker-php7-lamp
Docker example with Apache, Mysql, PhpMyAdmin and Php

## Usage

1. Open in background

```
docker-compose up -d
```

2. Open apache at http://localhost:8081, And you should see "It Works!" in page.

3. Open phpmyadmin at http://localhost:8887, Enter for Account: "root" & Password: "test".


## Default Settings

- **web**

  name: "php-apache-web"

  version: 7.3

  rewriteEngine: On

  folder: "htdocs"

  port: 8081

- **phpmyadmin**

  name: "php-apache-admin"

  version: latest

  user: "root"

  password: "test"

  port: 8887

- **mysql**

  name: "php-apache-mysql"

  version: latest

  user: "root"

  password: "test"

  folder: "mysql"

  port: 3306