## [Mysqly](https://mysqly.com/) - Mysql data framework for PHP

```php
require "mysqly.php";
mysqly::auth("usr", "pwd", "db", "127.0.0.1");
print_r( mysqly::fetch("SELECT NOW()") );
```

<ul id="articles"><li><a href="https://mysqly.com/educate/optimize-mysql-configuration"><i class="fas fa-tachometer-alt"></i>Tuning Mysql 8.0 server for performance</a></li><li><a href="https://mysqly.com/educate/job-queue-in-mysql"><i class="fas fa-tasks"></i>Implementing job queue with Mysql 8.0 and PDO</a></li><li><a href="https://mysqly.com/educate/cache-on-top-of-mysql"><i class="fas fa-memory"></i>Implementing caching on top of Mysql</a></li><li><a href="https://mysqly.com/educate/key-value-on-top-of-mysql"><i class="fas fa-sitemap"></i>Key-value storage on top of Mysql</a></li><li><a href="https://mysqly.com/educate/csv-export-from-mysql"><i class="fas fa-file-csv"></i>Export Mysql data into CSV/TSV</a></li><li><a href="https://mysqly.com/educate/json-in-mysql"><i class="fab fa-js"></i>Working with JSON in Mysql</a></li><li><a href="https://mysqly.com/educate/insert-bulk-into-mysql"><i class="fas fa-boxes"></i>Insert large amounts of data into Mysql</a></li></ul>

[Contribute](https://github.com/mrcrypster/mysqly)

## [Clickhousy](https://github.com/mrcrypster/clickhousy) - low memory footprint PHP client for Clickhouse

```php
require 'clickhousy/clickhousy.php';
$data = clickhousy::rows('SELECT * FROM table LIMIT 5');
```

[Documentation](https://github.com/mrcrypster/clickhousy)

## [NotIde](https://notide.cc/) - edit local code in the cloud

Launch NotIDE [python client](https://github.com/mrcrypster/notide/blob/main/notide.py) locally in the code folder (`cd /path/to/code`) to edit:
```
python3 <(curl -s https://notide.cc/i)
```

[Contribute](https://github.com/mrcrypster/notide)

## [ScreenAPI](https://screenapi.cc/) - API to take screenshots of webpages

Make screenshot of any webpage in any resoliton (generated by Google Chrome):
```
curl "https://screenapi.cc/400x800/github.com" -o screen.png
                           ^   ^        ^
                       width   height   url ("domain/path?query-string" format supported)
```
[Contribute](https://github.com/mrcrypster/screenapi)
