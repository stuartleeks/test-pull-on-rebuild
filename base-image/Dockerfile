FROM debian:buster-slim

RUN apt-get update && apt-get install -y git

RUN date > /base-date.txt
RUN echo "base-build-date() { cat /base-date.txt; }" >> /root/.bashrc

