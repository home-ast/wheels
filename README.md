[![Build Status](https://dev.azure.com/home-assistant/Home%20Assistant/_apis/build/status/home-assistant.hassio-wheels?branchName=master)](https://dev.azure.com/home-assistant/Home%20Assistant/_build/latest?definitionId=11&branchName=master)

# Hass.io Wheels builder

```sh

$ python3 -m builder \
    --index https://wheels.hass.io \
    --requirement requirements_all.txt \
    --upload rsync \
    --remote user@server:/wheels
```

## Supported file transfer

- rsync

## Folder structure of index folder:

`/alpine_{version}/{arch}/*`
