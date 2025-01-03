FROM postgres:16.4

RUN apt-get update \
  && apt-get install -y postgresql-16-postgis \
  && rm -rf /var/lib/apt/lists/*
