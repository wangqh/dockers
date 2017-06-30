FROM chanhw/base:edge

RUN echo '@edge https://mirrors.ustc.edu.cn/alpine/edge/main' >> /etc/apk/repositories
# RUN echo '@edge http://nl.alpinelinux.org/alpine/edge/main' >> /etc/apk/repositories
# RUN echo '@community http://nl.alpinelinux.org/alpine/edge/community' >> /etc/apk/repositories

RUN apk update && apk upgrade \
  && apk add nodejs@edge \
  && rm -rf /var/cache/apk/*
