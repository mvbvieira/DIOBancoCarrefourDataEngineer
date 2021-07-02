ARG BASE_CONTAINER=jupyter/minimal-notebook

FROM $BASE_CONTAINER

LABEL author="Marcos Vieira"

USER root

COPY requirements.txt .

RUN pip install -r requirements.txt

USER $NB_UID
