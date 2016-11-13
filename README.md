# Linux Mint Docker CI Image

[![](https://images.microbadger.com/badges/image/vcatechnology/linux-mint-ci.svg)](http://microbadger.com/images/vcatechnology/linux-mint-ci "Image Layers") [![](https://images.microbadger.com/badges/version/vcatechnology/linux-mint-ci.svg)](http://microbadger.com/images/vcatechnology/linux-mint-ci "Image Version") [![](https://images.microbadger.com/badges/license/vcatechnology/linux-mint-ci.svg)](https://microbadger.com/images/vcatechnology/linux-mint-ci "Image License")  [![](https://images.microbadger.com/badges/commit/vcatechnology/linux-mint-ci.svg)](https://github.com/vcatechnology/docker-linux-mint-ci "Image Commit")

This container derives from
[vcatechnology/linux-mint](https://hub.docker.com/r/vcatechnology/linux-mint) so that the
image has the latest [Linux Mint](https://www.linuxmint.com/) packages. It then
installs the some useful development packages.

Available on Docker Hub as [vcatechnology/linux-mint-ci](https://hub.docker.com/r/vcatechnology/linux-mint-ci/)

## `sudo`

The Docker image creates a user account 'build-server' with `sudo` permissions. The `sudo` password
is disabled to allow non-interactive sudo calls.
