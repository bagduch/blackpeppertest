# Test from Blackpepper



Simple Test from Blackpepper

## Install

Via Composer

``` bash
$ compsoer install 

## if composer.json missing

$ composer require bagduch/blackpepper:dev-master
```

## Usage

``` php
use bagduch\blackpepper\Csvloader;

//load all csv under directory .
$loader = new Csvloader('directory');

//load one csv under directory
$loader = new Csvloader('directory','filename');


//extend to Mysql other storage method, For later.
$loader = new MysqlLoader(connect);

$company = new Company($name, $url, $logo);

index.php is a example class.

```

## Unit Testing

Testing Implement into test. Some basic testing.

## Validation

Validation method can be implement by create functions in trait Validation

## Sort

Only one sort implement. 

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.


[link-packagist]:https://packagist.org/packages/bagduch/blackpepper
