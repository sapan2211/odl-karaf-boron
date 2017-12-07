FROM ubuntu:16.04

#EXPOSE 8101 8181 8080 6633 6640 6653
RUN set -eux; \
    apt-get update; \
    apt-get install --no-install-recommends -y\
    openjdk-8-jre-headless\
    wget\
    ;\
    wget https://nexus.opendaylight.org/content/groups/public/org/opendaylight/integration/distribution-karaf/0.5.0-Boron/distribution-karaf-0.5.0-Boron.tar.gz;\
    tar xf distribution-karaf-0.5.0-Boron.tar.gz ;\
    rm -f distribution-karaf-0.5.0-Boron.tar.gz ;\
    apt-get purge --auto-remove -y \
    wget\
    ;\
