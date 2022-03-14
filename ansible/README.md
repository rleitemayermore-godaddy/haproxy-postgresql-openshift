# Steps on the postgresql server side

### 1 - Add the script to a location, for example /opt/pgcheck.sh
### 2 - Add the xinetd config file to /etc/xinetd.d/pgcheck
### 3 - Add the following to /etc/services, please keep in mind that the service name needs to match the name in the xinetd service

```pgsqlchk	9200//tcp```
