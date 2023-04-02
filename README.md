# Docker Infrastructure
Infrastructure for locally development. It based on Nginx(HTTP only) and PHP-FPM services.

For correctly installation use https://github.com/BlackMaizeGod/install_docker_infrastructure.

### Notices:
- To connect to the Redis use: `redis-cli -h $(getContainerAddress redis) -p 6379 -a <password>`
- To connect to the Memcached use: `echo stats | nc $(getContainerAddress memcached) 11211`
