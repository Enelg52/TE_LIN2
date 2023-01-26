FROM python:3-alpine
LABEL hub_url="enelg/api-server"
COPY . /app
WORKDIR /app
ENTRYPOINT ["python3","socket_server.py"]