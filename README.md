# Docker Image

- [ipascual/docker-magento2-nginx](https://hub.docker.com/r/ipascual/docker-magento2-nginx/)

# Description

This repo is a fork from [MagenInferno-Nginx](https://github.com/mageinferno/docker-magento2-nginx) to apply some changes focused in local development on Magento2.

# What's in this image?

This image installs the following:

- `nginx`

# Variables

The following environment variables are used for Nginx configuration:

- `PHP_HOST`: (default: `phpfpm`) The hostname of the PHP container.
- `PHP_PORT`: (default: `9000`) The port of the PHP container.
- `APP_MAGE_MODE`: (default: `default`) Set the appropriate MAGE_MODE.

# Docker Compose

Please see [https://github.com/mageinferno/magento2-docker-compose](https://github.com/mageinferno/magento2-docker-compose) for more detailed instructions and an example development environment using Docker Compose.
