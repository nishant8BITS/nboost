FROM tensorflow/tensorflow:1.15.0-gpu-py3

LABEL maintainer="colethienes@gmail.com"

RUN pip install --upgrade pip
RUN pip install nboost[tf]

ENTRYPOINT ["nboost"]


