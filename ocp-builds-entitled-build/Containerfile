FROM registry.redhat.io/ubi9/ubi:9.5-1739751568

RUN dnf install -y --enablerepo rhocp-4.17-for-rhel-9-x86_64-rpms openshift-clients \
    && dnf clean all

RUN oc version