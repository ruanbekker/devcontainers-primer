ARG PYTHON_VERSION=3.8
ARG DISTRO_NAME=bullseye
FROM python:${PYTHON_VERSION}-${DISTRO_NAME}

RUN apk --no-cache add git

COPY ../src/requirements.txt /tmp/requirements.txt

CMD ["sh"]
