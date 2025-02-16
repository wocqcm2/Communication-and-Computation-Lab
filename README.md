# Project Name

Lab Website

if your are using windows, you need to use the following command to build the docker image
use    "docker build --tag lab-website-renderer:latest --file ./.docker/Dockerfile ." to                 build the docker image

use  "docker run --name lab-website-renderer --init --rm --interactive --tty --publish 4000:4000 --publish 35729:35729 --volume "$(pwd):/usr/src/app" lab-website-renderer:latest" to run the website


if you are using linux including wsl, use ./lab-website/.docker/run.sh to build and run the website
