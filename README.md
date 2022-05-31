# PiHole in a docker for my suksiboksi server setup

This repository contains Docker container and docker-compose configuration for running PiHole and Unbound together.

This package is inspired by somebody else's work, but since it's been quite some time I first started fiddling around with this, I have lost the link to the original work. Thanks whoever you are.

This setup requires some environment variables:

```
PIHOLEPASSWORD=<SOME_PASSWORD>
DOCKER_NETWORK=<YOUR_DOCKER_NETWORK, e.g. my_network>
```
