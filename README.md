# Docker Examples

Repository where i store all independent services i need for developing eg: database

To run a service:

```sh
cd {to_service_directory}
```

Then run:

```sh
docker compose build && docker compose up -d
```

For example: `cd mariadb && docker compose up -d`

Available Tools:

- Mariadb
- Mongo
