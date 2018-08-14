FROM python:3.6-alpine3.7
RUN pip install torndb
RUN pip install kazoo
RUN pip install tornado
RUN pip install thrift
RUN pip install jieba
RUN cp /usr/local/lib/python3.6/configparser.py /usr/local/lib/python3.6/ConfigParser.py
RUN apk add python3-dev && apk add mysql-dev && apk add gcc && apk add musl-dev && pip install MySQL-python && apk del gcc && apk del musl-dev && apk del python3-dev
