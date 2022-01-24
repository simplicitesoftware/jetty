Jetty for Simplicit&eacute;&reg;
================================

This repository contains an optimized and customized version of Eclpse Jetty&reg; suitable for the Simplicit&eacute;&reg; platform.

Additional JARs
---------------

Some additional JARs have been included in the `lib/ext` folder:

- `commons-dbcp-1.x.jar`
- `commons-pool-1.x.jar`
- `mysql-connector-java-x.y.z-bin` the MySQL/MariaDB JDBC driver
- `postgresql-x.y.z` the PostgreSQL JDBC driver

Usage
-----

The server is configured to use plain HTTP on the `8080` port.

If you deploy it behind a reverse proxy you must configure `default/start.d/server.ini` and `default/start.d/http.ini` accordingly.

