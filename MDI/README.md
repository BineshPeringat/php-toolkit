# MySQL Database Interface (MDI)
MDI is a part of PHP Tookit by Binesh Babu Peringat.

This tool tries to simplify the process of interacting with a MySQL database and is built for functionality rather than speed.

> Internally MDI is just a wrapper around the [PHP MySQLi](http://php.net/manual/en/book.mysqli.php) extension.

<br />

## Requirements
- PHP v5.5.x
- MySQLi extension

<br />

## So, what's all the fuss about?
I actually hate to duplicate code and when using MySQLi extension, I end up having to duplicate code. So this tool gets you what you want without digging through the muck.

This tool takes care of the following -
- Creating and maintaining server connection.
- Database switching.
- Building search and operational queries.
- Batch querying.
- Result retrieval and type conversion.
- Basic memory management.
