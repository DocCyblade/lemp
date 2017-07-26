LEMP Stack - Web Stack (Nginx + MariaDB)
==============================

LEMP stack is a popular open source web platform commonly used to run
dynamic web sites and servers. It includes Linux, Nginx, MariaDB, and
PHP/Python/Perl and is becoming another platform of choice for
development and deployment of high performance web applications which
require a solid and reliable foundation.

LEMP stack includes all the standard features in `TurnKey Core`_, and on
top of that:

- SSL support out of the box.
- PHP, Python and Perl support for MariaDB
- PHP-FPM FastCGI
- PHP development helpers

    - `phpsh`_: interactive shell
    - `php5-xdebug`_: debugging and profiling
    - `php-pear`_: php extension and application repository
    - php5-cli: command-line interpreter

- As of Debian stretch (v9) MySQL was replaced with `MariaDB`_
- `Adminer`_ administration frontend for MariaDB (listening on port
  12322 - uses SSL).
- `Postfix`_ MTA (bound to localhost) to allow sending of email from web
  applications (e.g., password recovery).
- Webmin modules for configuring PHP, MariaDB and Postfix.

A separate `LEPP stack`_ appliance features PostgreSQL instead of MariaDB.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, Adminer: username **root**

.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _phpsh: http://www.phpsh.org/
.. _php5-xdebug: http://xdebug.org/
.. _php-pear: http://pear.php.net/
.. _Adminer: http://www.adminer.org/
.. _Postfix: http://www.postfix.org/i
.. _MariaDB: https://mariadb.com/kb/en/mariadb/mariadb-vs-mysql-compatibility/
.. _LAPP stack: https://www.turnkeylinux.org/lapp
