# Influxdb Docker

Docker container for influxdb

## Development Installation

1. Download the code from github

```bash
git clone https://github.com/LCBRU/influxdb_docker.git
```

2. Enviroment

Copy the file `example.env` to `.env`.  The values in the
example.env should be fine, but you can change them if you want.

3. Further Configuration

See the [InfluxDb Docker documentation](https://docs.docker.com/samples/library/influxdb/)
for more configuration options.

## Building

To build the development instance, use the command:

```bash
docker-compose build
```

## Running

To run the development instance, use the command:

```bash
docker-compose up
```