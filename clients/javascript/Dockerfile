FROM python:3.8-alpine
RUN mkdir /apps
ADD index.html /apps
ADD start.sh /apps
RUN rm -rf /tmp/* /var/cache/apk/*
WORKDIR /apps
EXPOSE 9999
ENTRYPOINT ["sh","-C","start.sh"]