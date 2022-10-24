# 200 - Requirements

We strongly recommend:

- PHP 7.3 or higher
- MySQL 5.7 or higher (or Percona/MariaDB equivalent)
- SSL encryption (check out LetsEncrypt)

If your server is not running PHP 7.1 or higher, you should address this soon. PHP 7.0 has reached end of life and will no longer receive security patches. Vanilla’s support for PHP 7.0 will end soon.

Our minimum requirements are now:

- PHP 7.1 or newer. (This changed to 7.2 in 2020.)
- PHP extensions mbstring (--enable-mbstring), cURL (--with-curl), GD (on by default), and PDO (on by default).
- To import into Vanilla, you need MySQLi (--with-mysqli).
- To use our social plugins, you need OpenSSL.
- MySQL 5.0 or newer (or Percona/MariaDB equivalent).
- MySQL strict mode disabled.

Vanilla ships with a .htaccess file required for Apache support. Using nginx or IIS may require additional configuration. To learn more, see nginx.
