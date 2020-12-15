FROM python:3.8-alpine
RUN mkdir /apps
ADD client1.py /apps
ADD requirements.txt /apps
RUN rm -rf /tmp/* /var/cache/apk/*
WORKDIR /apps
RUN pip3 install -r requirements.txt
ENTRYPOINT ["python3","client1.py"]