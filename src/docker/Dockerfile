FROM registry.access.redhat.com/ubi7/ubi-minimal:latest

LABEL BASE_IMAGE="registry.access.redhat.com/ubi7/ubi-minimal:latest"
LABEL JAVA_VERSION="11"

RUN microdnf install --nodocs java-11-openjdk-headless && microdnf clean all