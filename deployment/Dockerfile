FROM quay.io/baguette.io/baguette-base:latest
# Docker
RUN apk add docker
# Install the module
USER 1890
RUN pip install --user baguette-messaging[postgres]
RUN pip install --user baguette-build
CMD ["/home/baguette/.local/bin/farine" ,"--start=cuisson"]