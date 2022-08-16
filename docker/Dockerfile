
FROM ubuntu:20.04

RUN apt-get update && DEBIAN_FRONTEND=noninteractive TZ=Etc/UTC apt-get -y install tzdata && apt-get -y install git \
datalad \
git-annex \
&& rm -rf /var/lib/apt/lists/*

