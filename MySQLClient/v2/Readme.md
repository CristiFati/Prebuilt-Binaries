*MySQLClient 2* binaries
------------------------

- Built with *MariaDB*
    1. [[MariaDB.DLM]: Community Server](https://dlm.mariadb.com/browse/mariadb_server/)
        1. Download binary (*.zip*), install (unpack) it and set ***MYSQLCLIENT_CONNECTOR***
        2. Download sources and build custom mariadbclient.lib (if required)
- Sources checked out in a branch from  [[GitHub]: PyMySQL/mysqlclient - MySQL/MariaDB connector for Python](https://github.com/PyMySQL/mysqlclient) (in a forked *repo* - select / checkout the appropriate tag for each version)
    - Apply on top (if required - check *#i.b.* (above)):
        - [[GitHub]: CristiFati/mysqlclient - fix: MariaDB include paths](https://github.com/CristiFati/mysqlclient/commit/fca567713d9b4e15277088e0f42295748df82e3c)
        - [[GitHub]: CristiFati/mysqlclient - feat: override mariadbclient.lib path](https://github.com/CristiFati/mysqlclient/commit/0985c09f857088e858999960222f2badfb143e22)
        - [[GitHub]: CristiFati/mysqlclient - feat: customize zlib path (required by mariadbclient)](https://github.com/CristiFati/mysqlclient/commit/bbaf96f78f14cc45e9bd7c1d22bf111705c0ae28)
    - Set the apropriate environment variables

- ***v2.2.6*** (*pc032*):
    - *MariaDB **11.6.2***
    - *ZLib 1.3.1* (also available in this *repo*)

**Platforms**:
- *Windows*

