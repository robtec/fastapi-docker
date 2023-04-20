# FastAPI Docker

Docker container for a FastAPI app

## Setup


Build the image
```
docker build -t fastapi-image .
```

## Running
```
# docker compose (preferred)

docker compose up -d --build

# docker

docker run -p 8000:8000 fastapi-image
```

## Docs

- FastAPI Docs - https://fastapi.tiangolo.com/tutorial/first-steps/
- Github Actions - https://docs.docker.com/build/ci/github-actions/examples/
