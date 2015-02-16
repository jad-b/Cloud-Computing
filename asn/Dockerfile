FROM debian:jessie

RUN apt-get update && apt-get install -y \
    g++ \
    make

# Safer:
# COPY mp1 /mp1
# Faster:
VOLUME /mp1

WORKDIR /mp1
