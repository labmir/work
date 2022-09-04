FROM python:3.7-alpine
WORKDIR /code
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
RUN apk add curl
HEALTHCHECK CMD curl --fail http://localhost:8001 || exit 1
CMD ["python", "hello_server.py"]