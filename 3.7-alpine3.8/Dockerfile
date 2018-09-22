FROM joyzoursky/python-chromedriver:3.7-alpine3.8

RUN apk --update add tzdata && \
    cp /usr/share/zoneinfo/Asia/Tokyo /etc/localtime && \
    apk del tzdata && \
    rm -rf /var/cache/apk/*
ENV LANG ja_JP.UTF-8
