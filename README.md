# docker-phpPgAdmin
phpPgAdmin is a web-based administration tool for PostgreSQL.

To use it:

`
docker run --name phpPgAdmin -v "./config.inc.php:/var/www/html/conf/config.inc.php" -d migolo/docker-phppgadmin
`
