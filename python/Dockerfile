FROM python:3.8
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
#RUN yum install python-devel mysql-community-devel
RUN pip install -r requirements.txt
ADD . /code/

