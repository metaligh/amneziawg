![Icon](https://docs.amnezia.org/ru/img/logo-with-a-w-glow.svg)
# AmneziaWG VPN Key Delegation and User Management with QR

This archive contains files for **AmneziaWG VPN key delegation and user management scripts**.

[Docker Hub Repository](https://hub.docker.com/repository/docker/metaligh/amneziawg/)

## Installation Instructions

1. Extract the archive to `/opt/amneziawg/`.
2. Mount this volume to your container.
3. Proceed with the `awguser` command.

Alternatively, you can use this key generator on your host system at `/etc/amnezia/amneziawg/`.

### Dependencies

Before running the `awguser` script, install `qrencode`:

```bash
apt install qrencode
```
A full description of how to use the scripts can also be found in the `readme` file of the archive.
