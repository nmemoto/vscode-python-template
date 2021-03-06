ARG VARIANT="3"
FROM mcr.microsoft.com/vscode/devcontainers/python:0-${VARIANT}

RUN python -m pip install --upgrade pip && \
    pip install pylint && \
    pip install jupyterlab && \
    jupyter serverextension enable --py jupyterlab
