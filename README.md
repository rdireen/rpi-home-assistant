
# Home Assistant Docker image for Raspberry Pi
Note this is a fork from lroguet's repo. Go to his repo for the best version of the code. 
Forked from https://github.com/lroguet/rpi-home-assistant

## Description
A Dockerfile for a Raspberry Pi with [Home Assistant](https://home-assistant.io/).

## Usage
### One-liner
`docker run -d --name hass --net=host -v /etc/localtime:/etc/localtime:ro -v /home/pi/home-assistant/configuration:/config rdireen/rpi-home-assistant:latest`

## Links
* [Home Assistant, Docker & a Raspberry Pi](https://fourteenislands.io/home-assistant-docker-and-a-raspberry-pi/)
* [Docker public repository](https://hub.docker.com/r/rdireen/rpi-home-assistant/)
* [Home Assistant](https://home-assistant.io/)
