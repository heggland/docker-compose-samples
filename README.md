# docker-compose samples

> **Note**: 
> The examples are intended for use in local development environments.
> If you want to use them in production, you should change the configurations accordingly.
> See docker-compose file for details usernames, passwords, ports, volumes and other configurations.

## Requirements
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Examples

#### MySQL
```bash
docker-compose -f docker-compose-mysql.yml up -d --build
```
for more information, see [MySQL](https://hub.docker.com/_/mysql)

#### PostgreSQL
```bash
docker-compose -f docker-compose-postgres.yml up -d --build
```
for more information, see [PostgreSQL](https://hub.docker.com/_/postgres)

## Contributing
Licensed under the MIT License. Feel free to use it as a template for your own app. Contributions are welcome.

    