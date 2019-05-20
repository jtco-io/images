ARG IMAGE

FROM $IMAGE

RUN mkdir -p $WORK_DIR && \
    python3 -m venv $VENV_DIR && \
    pip install --upgrade --no-cache-dir pip pipenv

WORKDIR $WORK_DIR
