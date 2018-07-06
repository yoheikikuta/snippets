FROM python:3.6
MAINTAINER Yohei Kikuta <diracdiego@gmail.com>

RUN apt-get update

RUN pip install --upgrade pip

RUN pip install \
    jupyter \
    numpy \
	pillow \
	tensorflow \
	keras

WORKDIR /work

ENTRYPOINT ["/bin/bash"]""]
