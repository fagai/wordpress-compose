# WordPress開発用DockerCompose

* Nginx-Proxy
* Nginx
* Wordpress:PHP7.3-FPM
* MySQL:8

## Usage

```
$ docker-compose up -d
```

## use WP-CLI

```
$ docker run -it --rm --volumes-from container_name --network container:container_name wordpress:cli
```

container_nameは`docker ps`コマンドで調べて入れてください。

## License

MIT

