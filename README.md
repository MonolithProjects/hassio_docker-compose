## Requirements
```
docker-ce
bash
jq
curl
avahi
dbus
```
**Note:** Hass images used in this docker-compose file require machine with x86_64 architecture (check it by running `uname -m` command)


## Run
If you want to use standard folder for Hass-supervisor data:
```
docker-compose up
```

If you want to specify folder for Hass-supervisor data:
```
SUPERVISOR_SHARE=/yourfolder docker-compose up
```
