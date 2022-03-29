FROM oraclelinux:8-slim

# Update and install required packages
RUN microdnf -y update
RUN  microdnf -y install wget tar

# Create a working directory to download the telegraf package
WORKDIR /telegraf/