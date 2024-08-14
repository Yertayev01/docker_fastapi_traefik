python -m venv venv

activate venv

docker-compose -f docker-compose.prod.yml up -d --build

link:
https://testdriven.io/blog/fastapi-docker-traefik/