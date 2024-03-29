# php8-nginx-docker for laravel or Codeigniter
PHP 8 + JIT development environment enabled, Nginx, MySQL DBMS and Adminer

**Prerequisites:** Have Docker and Docker-compose installed.


[Installing Docker on Windows 10](https://mundodacomputacaointegral.blogspot.com/2019/10/instalando-o-docker-no-windows.html)

[Installing Docker and Docker-compose on Linux (any distro)](https://mundodacomputacaointegral.blogspot.com/2019/10/instalando-docker-e-docker-compose-no-Linux.html)

After installing Docker and Docker-compose, follow the procedures:

1. Fork this repository

2. Clone the forked repository

```
git clone https://github.com/youre_account/youre_forked_repo .
```

3. Access the directory where you saved the repository clone

4. Run `docker-compose up -d` for start server

The HOST's src directory is the volume mapped to the CONTAINER's /var/www/html directory. So, it is in the src directory that you must save the .php files.

Browse `http://localhost/info.php` and see PHP enabled extensions. Browse `http://localhost/` and see Hellow world

5. Run `docker-compose down` for stop server

Access the web tool to manage the database in the MySQL DBMS, access http://localhost:8080 the access credentials, found in the docker-compose.yml file

## Install for laravel

[See laravel tree](https://github.com/wpdew-com/php8-nginx-docker/tree/laravel)

## Install for Codeigniter

[See Codeigniter tree](https://github.com/wpdew-com/php8-nginx-docker/tree/codeigniter)

Done!
