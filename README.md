# Dockerized python-flask + Qdrant app

Container for Python app with Flask routing and Qdrant backend.

## Usage

Download the repository and build the container with:

```bash
docker-compose up --build
```

Flask: http://localhost:8000

Qdrant: http://localhost:6333

## Todo

- Where to add the command for pip install or requirements for addons?
- integration with DDEV?
- Autoreloading of the app when the code changes.
