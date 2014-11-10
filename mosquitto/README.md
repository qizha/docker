Mosquitto
=========

Docker build file for mosquitto. This docker file is based on
debian latest and mosquitto version 1.3.5.

Get it
======
sudo docker pull qizh/mosquitto

Run it
======
sudo docker run -p 1883:1883 --name mosquitto -d qizh/mosquitto
