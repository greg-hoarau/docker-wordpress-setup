# docker-wordpress-setup

A small configuration to develop a wordpress theme (or plugins) with docker.
This project is only suitable for small development.

## Prerequisites

Make sure you have already installed both Docker Engine and Docker Compose.

## Installation

Clone the project and run:

```
git clone https://github.com/greg-hoarau/docker-wordpress-setup.git
cd docker-wordpress-setup
```

Then, run the different containers with docker-compose:

```
docker-compose up -d
```

Your wordpress is now accessible from [localhost](http://localhost:8000/).

## Acknowledgments

Thanks to David Yeiser for his [tutorial "Docker + WordPress Setup"](https://davidyeiser.com/tutorials/docker-wordpress-theme-setup) !
