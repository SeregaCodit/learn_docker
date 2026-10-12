FROM ros:lyrical

RUN apt-get update && apt-get install -y nano \
    && rm -rf /var/lib/apt/lists/*

COPY config/ /site_config/ 