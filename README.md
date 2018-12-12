# rpi-pigpio
Dockerfile for pigpio on Raspberry Pi.
The image is base on Alpine one.

## Start the container
```bash
docker run -it --cap-add=SYS_ADMIN --privileged --device /dev/mem sourit/pi-gpio /bin/sh
```
