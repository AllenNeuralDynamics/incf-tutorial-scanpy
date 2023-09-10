# hash:sha256:96478571107ef718409d634623039942dd3427f5cbacae96f4e37067fdfe08c0
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.6.1-miniconda4.12.0-python3.9-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    leidenalg==0.10.1 \
    scanpy==1.9.4
