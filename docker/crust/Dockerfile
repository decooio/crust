# Build crust image
FROM ubuntu:20.04

RUN apt-get update
RUN apt-get install -y openssl
COPY crust/crust /opt/crust/crust
COPY crust/run.sh /opt/run.sh

WORKDIR /opt/crust/
CMD /opt/run.sh
