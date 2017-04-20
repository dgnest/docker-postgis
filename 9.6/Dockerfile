FROM dgnest/postgres:9.6

# File Author / Maintainer
MAINTAINER DGNEST <@dgnest>

RUN apt-get update \
    && apt-get -y install postgis \
    && apt-get autoclean \
    && apt-get autoremove \
    && rm -rf /var/lib/apt/lists/*
