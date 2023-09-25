FROM jupyter/datascience-notebook:python-3.8.4

USER root
RUN apt-get update && apt-get install -y git

COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt