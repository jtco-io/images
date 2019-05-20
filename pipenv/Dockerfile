ARG PYTHON_VERSION
ARG ALPINE_VERSION
ARG DOCKER_REGISTRY_ORG=jtcoio

FROM ${DOCKER_REGISTRY_ORG}:$PYTHON_VERSION-alpine$ALPINE_VERSIONE

RUN mkdir -p $WORK_DIR && \
    python3 -m venv $VENV_DIR && \
    pip install --upgrade --no-cache-dir pip pipenv

WORKDIR $WORK_DIR
