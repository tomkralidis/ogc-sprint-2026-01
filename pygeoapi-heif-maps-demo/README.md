# pygeoapi-heif-maps-demo

This demo implements a pygeoapi OGC API - Maps provider for HEIF

## Running

```bash
# build
make build
# start pygeoapi
make up
# see API
curl http://localhost:8999  # or open in a web browser
# stop pygeoapi
make down
```

## Notes

- `docker-compose.yml` has a volume mapping for HEIF data that needs to be updated accordingly (no test data is included in this repository)
