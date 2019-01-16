Create directories on host
Directories are created on the host to persist data for the containers to volume mount from the host.

mysql: The database files for MariaDB

wordpress: The WordPress media files

logs/nginx: The Nginx log files (error.log, access.log)

`mkdir -p  logs/nginx/ mysql/ wordpress/`

host: localhost
mysql login: root
mysql pass: password
port:3306