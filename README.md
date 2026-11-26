# Uptime Herald Starter Files

These are the starter files for [Uptime Herald](https://github.com/herald-stack/uptime-herald), the configuration files, Docker Compose files, and example environment files that the [Quick Start Guide](https://uptimeherald.org/docs/quick-start/) has you download. This repository mirrors the download site, `get.uptimeherald.org`, so a path here is the same path there.

## What's Here

Everything is in `releases/`, with a folder for each version of Uptime Herald and a folder named `latest`. Each of those holds the same three folders:

- `config/` holds the default configuration files (`alerts`, `config`, `maintenance`, `monitors`, `tags`, and `theme`) and `credentials.default.ini`.

- `compose/` holds `docker-compose.yaml` and `docker-compose-external.yaml`, with a folder for each database (`mariadb` and `postgres`).

- `env/` holds `example.env` and `example-external.env`, with a folder for each database.

## Choosing a Version

Open the folder for the version of Uptime Herald you run, for example `releases/1.0.0/`. The compose files in it are pinned to that version.

The compose files in `releases/latest/` use the `latest` image tag instead, so they follow whichever version is newest.

## Documentation

How to use each file is covered in the [documentation](https://uptimeherald.org/docs/).

## Reporting a Problem

Open an issue at [issues.uptimeherald.org](https://issues.uptimeherald.org).

## License

Uptime Herald is licensed under the GNU Affero General Public License version 3. See `LICENSE`.

