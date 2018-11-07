# Docker Utils

A swiss army knife for common docker containers.

## Installation
Copy `docker-utils` to a location on your path, and make it executable:

```
sudo curl -L https://raw.githubusercontent.com/CUUATS/docker-utils/master/docker-utils -o /usr/local/bin/docker-utils
sudo chmod +x /usr/local/bin/docker-utils
```

## Usage

```
docker-utils command container
```

## Commands

### MySQL (MariaDB)
* `mysql-dump`
* `mysql-restore`

### PostgreSQL

* `postgres-createdb`
* `postgres-dropdb`
* `postgres-dump`
* `postgres-dumpall`
* `postgres-psql`
* `postgres-restore`

## Credits
Docker Utils was developed by Matt Yoder for the Champaign County Regional
Planning Commission (CCRPC).

## License
Docker Utils is available under the terms of the [BSD 3-clause
license](https://github.com/CUUATS/docker-utils/blob/master/LICENSE.md).
