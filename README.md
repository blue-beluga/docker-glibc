
# [<img src=".bluebeluga.png" height="100" width="200" style="border-radius: 50%;"/>](https://github.com/blue-beluga/docker-glibc) bluebeluga/glibc

Alpine Linux image, that contains glibc to enable compiled tools (e.g. OracleJDK) work on Alpine.

## Installation and Usage

```
docker pull bluebeluga/glibc
docker run bluebeluga/glibc [options]
```

## Available Tags

* `latest`: Currently 2.23-r1
* `2.23-r1`

## Tests

Tests are run as part of the `Dockerfile` build. To execute them separately within a container, run:

```
bats test
```

Or during the build process using the following command:

```
make test
```

## Deployment

To push the Docker image to the registry, run the following command:

```
make push
```
