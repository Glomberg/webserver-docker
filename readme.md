# Nginx stable + PHP 8.3 + MySQL 8.1 + PhpMyAdmin latest = ready clean web server

## For local dev usage only! Not for production use!

1) Clone the repository
2) Create your own .env file like .env-example and define variables in the .env
3) Run docker containers `docker-compose up -d`
4) Add the item in the hosts file as defined `${INSTANCE_NAME}`. For example `127.0.0.1 website.loc`
5) Open the browser and go host as defined `${INSTANCE_NAME}`. For example http://website.loc
6) Enjoy!

PhpMyAdmin side is on http://${INSTANCE_NAME}:8080
Server: `mysql`, username: `mysql`, password: `mysql`