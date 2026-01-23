SLiMS 9 Bulian
===============
SLiMS 9 Bulian - Australian and Myanmar enhancements. Details regarding the base software are below. 
This fork aims to provide additional translations of the admin interface and the OPAC, and enhanced Help files. 
As of 23/01/2026 the focus of this project is on providing increased language choice while maintaining compatibility with the official SLiMS9 development branch. 
Platform support for translation is being provided by Poeditor.com under their Open Source support license tier. 
Jim Richardson.
***************
SENAYAN Library Management System (SLiMS) version 9 Codename Bulian

SLiMS is free open source software for library resources management
(such as books, journals, digital document and other library materials)
and administration such as collection circulation, collection management,
membership, stock taking and many other else.

SLiMS is licensed under GNU GPL version 3. Please read "GPL-3.0 License.txt"
to learn more about GPL.

### System Requirements
- PHP version >= 8.1;
- MySQL version 5.7 and or MariaDB version 10.3;
- PHP GD enabled
- PHP gettext enabled
- PHP mbstring enabled

### Running Docker Development

Using docker for running requires Docker Desktop service, as it will use Docker to create the database.
Before run docker compose copy .env.example to .env for setting http port and maria db (db) port 
can be change on .env

You can run the test using this command :

```shell
docker compose up -d --build
```

Setting docker default can be change on docker-compose.yml
