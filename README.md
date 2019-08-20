# WordPress Sandbox

The intent of this repository is to provide a quick start environment for WordPress development through Docker containers.

## Getting Started

The `docker-compose.yml` file defines a WordPress web server, MySQL database server and also includes phpMyAdmin as a database management tool.

```
$ docker-compose up -d
```

## Development

The scaffolding for a custom plugin is included in the `src` directory. It maps to `wp-content/plugins/my-plugin` in the WordPress instance.