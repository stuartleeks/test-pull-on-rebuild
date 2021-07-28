
FROM ghcr.io/stuartleeks/test-pull-on-rebuild/devcontainer-base:main

RUN date > /image-date.txt
RUN echo "image-build-date() { cat /image-date.txt; }" >> /root/.bashrc

