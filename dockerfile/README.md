This repository simply contains a Dockerfile to build an image for Mcrouter. This file is based on the officially maintained Dockerfile with the only difference that it sets a specific version (currently 36.0.0). To use a different version, fork this repository and change the MCROUTER_BRANCH environment variable.

To build the image, run the following command:

docker build -t mcrouter:0.36.0 .