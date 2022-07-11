FROM python:3.8.10-buster
USER root
WORKDIR /home/projects

COPY etc/requirements_simple.txt /tmp/requirements_simple.txt
RUN pip install --upgrade pip setuptools && \
    pip install -r /tmp/requirements_simple.txt