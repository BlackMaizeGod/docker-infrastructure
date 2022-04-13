# Docker Infrastructure
Infrastructure for locally development. It based on Nginx(HTTP only) and PHP-FPM services.

For correctly installation use https://github.com/BlackMaizeGod/install_docker_infrastructure.

### Notices:
- For debug cli area into docker container - configure project inside suitable docker container via `export PHP_IDE_CONFIG="serverName=<SomeName>"`. Debug cli area outside docker container will works as expected, without any extra configurations.
