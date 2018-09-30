# dl_keras
Deep Learning exploration with Keras...

** OBSOLETE **

# Installation
We use a Docker box to run the development environment...

So first, install docker on your machine (Linux): 
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce

Next, install  the following ready-to-go docker image:

	docker pull floydhub/dl-docker:cpu

SIANA Git Repo
A siana git repo is available which contains config / test scripts.

Clone the repo in an appropriate working directory:

	git clone https://github.com/siana-systems/dl_keras.git

# Getting Started
The root of the siana repo contains a small bash/shortcut to start the docker with the recommended options:

cd to the working directly...

	./run_docker.sh

This will start docker in bash/interactive mode and share the current host directory to /root/sharedfolder in the docker image.
