FROM ubuntu:16.04

ARG XYZ
ENV ABC=$XYZ

WORKDIR /app
COPY . /app

RUN printenv
CMD ["/app/test.sh"]
