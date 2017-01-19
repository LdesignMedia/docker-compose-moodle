# Docker compose file for h5p running in Moodle

## Running

1. Clone this repository, and clone the [h5p moodle plugin](https://github.com/h5p/h5p-moodle-plugin) repository.
2. Edit [docker-compose.yml](docker-compose.yml) so that the volume points to the _moodle plugin_
3. Run with [docker-compose](https://docs.docker.com/compose/)

```bash
docker-compose up
```
