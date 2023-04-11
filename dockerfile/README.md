This repository simply contains a Dockerfile to build an image for Mcrouter. This file is based on the officially maintained Dockerfile with the only difference that it sets a specific version (currently 36.0.0). To use a different version, fork this repository and change the MCROUTER_BRANCH environment variable.

To build the image, run the following command:

docker build -t mcrouter:0.36.0 .


To build the image with exporter, please run

docker build -t mcrouter_exporter:0.2.0 . -f Dockerfile.exporter

### PLEASE CHECK THE REPO https://github.com/Dev25/mcrouter_exporter. Docker will be clone data from it

