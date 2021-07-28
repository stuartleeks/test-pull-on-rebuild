
FROM ghcr.io/stuartleeks/test-pull-on-rebuild/devcontainer-base:main

RUN date > /image-date.txt
RUN echo "image-build-date() { cat /image-date.txt; }" >> /root/.bashrc
RUN echo "info() { echo -n 'Base date:  ' && base-build-date && echo -n 'Image date: '  && image-build-date; }" >> /root/.bashrc
