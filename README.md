### Install

Since this repository is not connected to a private artifact repository, the JDBC driver must be installed manually.

```
mvn install:install-file -Dfile=ojdbc6-11.2.0.jar -DgroupId=com.oracle.jdbc -DartifactId=ojdbc6 -Dversion=11.2.0 -Dpackaging=jar
```

This should install the driver as follows:

```
➜  11.2.0 pwd
/Users/yoni/.m2/repository/com/oracle/jdbc/ojdbc6/11.2.0
➜  11.2.0 ll
total 6304
-rw-r--r--  1 yoni  staff  2739670 Feb 22 17:00 ojdbc6-11.2.0.jar
-rw-r--r--  1 yoni  staff      939 Mar  8 10:56 ojdbc6-11.2.0.pom.lastUpdated
-rw-r--r--  1 yoni  staff      859 Mar  8 10:56 ojdbc6-11.2.0.jar.lastUpdated
-rw-r--r--  1 yoni  staff      466 Mar  8 11:24 ojdbc6-11.2.0.pom
-rw-r--r--  1 yoni  staff      206 Mar  8 11:24 _remote.repositories
```
