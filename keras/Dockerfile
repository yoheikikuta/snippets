FROM python:3.6
MAINTAINER Yohei Kikuta <diracdiego@gmail.com>

RUN apt-get update

RUN pip install --upgrade pip

RUN pip install \
    jupyter \
    numpy \
    pillow \
    tensorflow==1.8.0

WORKDIR /
RUN git clone https://github.com/keras-team/keras.git && \
    git clone https://github.com/keras-team/keras-applications.git
RUN cd keras && python setup.py install
RUN cd keras-applications && python setup.py install

WORKDIR /work

ENTRYPOINT ["/bin/bash"]
