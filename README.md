# Docker image with Git and Python, based in Alpine

## Running an interactive session

```bash
docker run -it --rm eduardoshanahan/git_python
```

Or with Docker Compose

```bash
docker-compose run --rm shell
```

## Development

If you want to make some changes and version it, [bumpversion](https://pypi.python.org/pypi/bumpversion) is available

```bash
bumpversion patch
```