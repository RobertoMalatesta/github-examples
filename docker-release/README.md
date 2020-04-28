# Docker Release

This example demonstrates how you can use tags and docker to build and push a 
release image to Docker Hub.

To enable this as a GitHub action you will have to do the following:

1. Copy the contents of the docker-release.yml into a new or existing workflow
2. Adjust the image name
3. Add the DOCKER_USERNAME secret as a secret to your GitHub account
4. Add the DOCKER_PASSWORD secret as a secret to your GitHub account
