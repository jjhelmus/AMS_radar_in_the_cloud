FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
  git \
  wget

RUN apt-get update && apt-get install -y bzip2
RUN apt-get update && apt-get install -y sudo

# To keep setup_ec2.sh fast
RUN apt-get update && apt-get install -y gcc gfortran

EXPOSE 8888

# Build:
# docker build -t test .

# Run docker
# docker run -it --rm -p 8888:8888 -v`pwd`:/io test 

# Run notebook
# /root/miniconda3/envs/ams-workshop/bin/jupyter notebook --certfile=~/certs/mycert.pem --keyfile ~/certs/mycert.key
