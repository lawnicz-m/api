
# Table of Contents
1. [Installation](#menu-installation)



## Installation <a name="menu-installation"></a>

Preapare configuration by copy .env.dist and docker-compose.yml.dist

```bash
cp .env.dist .env;
cp docker-compose.yml.dist docker-compose.yml;
```
and replace `PATH_TO_APP` with real path of application.


Go to your project directory and run

```bash
docker-compose build;
docker-compose up -d;
```




```
dc down -v;dc build;dc up -d;dc exec php _composer create-project symfony/website-skeleton api-project;
```

