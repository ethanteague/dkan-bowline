# Bowline DKAN Implementation

## Requirements
1. [Docker](https://www.docker.com/)
  - Make sure you can successfully run docker commands without sudo. See [Ubuntu example](https://docs.docker.com/installation/ubuntulinux/#giving-non-root-access).
1. [Docker Compose](http://docs.docker.com/compose/)

See also the [wiki](https://github.com/davenuman/bowline/wiki) for [platform-specific instructions](https://github.com/davenuman/bowline/wiki/Platform-specific-instructions).

## Quick Start
```
git clone git@github.com:ethanteague/dkan-bowline.git dkan
cd dkan
. bin/activate
build
drush si dkan --no-halt-on-error --notify -y -v
drush uli
```
