# MSNoise-docker

This docker runs a python package for Monitoring Seismic Velocity Changes using Ambient Seismic Noise.

MSNoise is the first complete software package for computing and monitoring relative velocity variations using ambient seismic noise. MSNoise is a fully-integrated solution that automatically scans data archives and determines which jobs need to be done whenever the scheduled task is executed.

The full information about package can be found on: http://www.msnoise.org.

## This container contains

* [xfce](http://www.xfce.org/) - a lightweight desktop environment for UNIX-like operating systems
* [TigerVNC](http://tigervnc.org/) - a high-performance, platform-neutral implementation of VNC (Virtual Network Computing) 
* [noNVC](https://kanaka.github.io/noVNC/) - a HTML5 canvas vnc viewer
* [MSNoise](http://www.msnoise.org/) - Package for Monitoring Seismic Velocity Changes using Ambient Seismic Noise

## How To

### With Docker Hub

* `docker pull unigeocloud/msnoise`
* `docker run -p 6901:6901 -ti  unigeocloud/msnoise:latest`
* `firefox http://localhost:6901`

### Manual Build

* `docker build -t unigeocloud/msnoise:latest .`
* `docker run -p 6901:6901 -ti  unigeocloud/msnoise:latest:latest`
* `firefox http://localhost:6901`

## On DockerHub / GitHub

* [unigeocloud/msnoise on DockerHub](https://hub.docker.com/r/unigeocloud/msnoise/)
* [unigeocloud/msnoise on GitHub](https://github.com/unigeocloud/msnoise/)

