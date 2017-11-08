# Docker compose file for running a plugin in Moodle

## Running

1. Install [Docker Toolbox](https://www.docker.com/products/docker-toolbox).
2. Clone this repository.
3. Edit [docker-compose.yml](https://github.com/MoodleFreak/docker-compose-moodle/blob/131d7e302a34ddb13c79ac3fcc63a093684118b5/docker-compose.yml#L18) so that the volume points to the _moodle plugin_
4. Run with [docker-compose](https://docs.docker.com/compose/)

```bash
docker-compose up
```


## Inspiration

laradock (https://github.com/laradock/laradock)

docker-compose-h5p-moodle (https://github.com/tajakobsen/docker-compose-h5p-moodle)
