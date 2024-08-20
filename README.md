# Kingston OpenSource HomeAssistant Demo

A simple example of a HomeAssistant configuration.

This example is already configured with a set of demo devices and an administrator user whose home is set to Tilda's in Kingston.

username: `admin`
password: `admin`

## Requirements

- docker

## Bootstrapping

`cd` into this project directory and start the application with docker compose.

```sh
docker compose up
```

## Starting up on your own

It should be noted, this repository started only with the following in its tree:

```sh
./kos-ha-demo
 ├ README.md
 ├ docker-compose.yaml
 └ /config
```

Nothing in the `./config` directory.
Its only purpose was to map the volume into the HomeAssistant container.

Keep this in mind, for easy access to reosurces inside your own HA container, should you deploy this way as well.

Optionally, there exist [ready-to-buy RaspberryPis](https://www.home-assistant.io/yellow/) which comes with hardware specifically meant for home-automation, should you prefer that route.

It still requires technical prowess to set up, as Home Assistant is not initially installed.
