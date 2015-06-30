# Sickbeard for Raspberry Pi 2

This is a Dockerfile to set up [Sickbeard](http://sickbeard.com/).

# Usage

```shell
$ docker run \
  -p 8081:8081
  -v /mnt/data:/data
  -v ./config:/config
  nunofgs/rpi-sickbeard
```
