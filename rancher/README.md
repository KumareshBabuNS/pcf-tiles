# Rancher.io Tile for Pivotal Cloud Foundry


Install the Docker images to your local host:

```
$ docker pull rancher/server
```

Build the tile:

```
$ tile build
```

Upload to ops manager:

```
pcf import products/<tile .pivotal>
```
