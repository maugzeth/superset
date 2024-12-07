# Dedsol | Superset

## Getting Started

1. Clone this repo locally.
2. Run `docker compose -f docker-compose-image-tag.yml up --build`
3. Open up `http://localhost:8088`.

## Usage

### Configure Superset

To configure superset edit the file:

`superset/docker/pythonpath_dev/superset_config_docker.py`

To understand the base settings for our instance checkout:

`superset/docker/pythonpath_dev/superset_config.py`

Finally, to see all the options we can configure take a look at:

`superset/config.py`

### Connect Database 

To connect to any **local** database instance make sure to use:

`host.docker.internal`

As the address instead of `localhost` or `127.0.0.1`.
