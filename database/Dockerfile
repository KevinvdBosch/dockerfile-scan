FROM postgres:17.2

RUN apt-get update \
  && apt-get install -y postgresql-16-postgis \
  && rm -rf /var/lib/apt/lists/*
