FROM python:3.6
MAINTAINER Yohei Kikuta <diracdiego@gmail.com>

RUN apt-get update

RUN pip install --upgrade pip

RUN pip install \
    jupyter \
    numpy \
    pillow \
    matplotlib \
    tensorflow==1.8.0

WORKDIR /work

ENTRYPOINT ["/bin/bash"]
