# Gamer Network Fork of DB

## Notable additions

Two pretty hacky debug drivers which make tracing SQL a bit easier when performance tuning.

 - `mysqli_debug.php`
 - `mysql_debug.php`

Just specify `mysql_debug`, etc as the `phptype` option in your DSN. e.g.

```
$dsn = array(
		"phptype" => "mysqli_debug",
		"hostspec" => "localhost",
		"database" => "...

```
