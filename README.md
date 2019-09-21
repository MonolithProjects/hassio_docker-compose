[![Build Status](https://travis-ci.org/MonolithProjects/hassio_docker-compose.svg?branch=master)](https://travis-ci.org/MonolithProjects/hassio_docker-compose)
[![Actions Status](https://github.com/MonolithProjects/hassio_docker-compose/workflows/Docker_test_build/badge.svg)](https://github.com/MonolithProjects/hassio_docker-compose/actions)  

## Requirements
```
docker-ce
docker-compose
avahi
dbus
```
**Note:** Hass images used in this docker-compose file require machine with x86_64 CPU architecture (check it by running `uname -m` command)


## Run
If you want to use standard folder for Hass-supervisor data (defauld is in /usr/share/hassio - needs to be created):
```
docker-compose up -d
```

If you want to specify folder for Hass-supervisor data:
```
SUPERVISOR_SHARE=/yourfolder docker-compose up -d
```
