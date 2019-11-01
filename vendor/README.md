# Test from Blackpepper



Simple Test from Blackpepper

## Install

Via Composer

``` bash
$ composer require bagduch/blackpepper:dev-master
```

## Usage

``` php
use bagduch\blackpepper\Csvloader;

//load all csv under directory .
$loader = new Csvloader('directory');

//load one csv under directory
$loader = new Csvloader('directory','filename');


//extend to Mysql other storage method

$company = new Company($name, $url, $logo);



```



## Validation

Validation method can be implement by create functions in trait Validation

## Sort

Only one sort implement.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.


[link-packagist]:https://packagist.org/packages/bagduch/blackpepper
