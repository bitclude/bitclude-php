# Bitclude SDK
It is php version of [ccxt library](https://github.com/ccxt/ccxt) including only bitclude exchange

## Instalation
Download source, go to it's directory and install deps with composer.

It may be neccessary to install and enable following php modules by hand:
- cURL
- mbstring (using UTF-8 is highly recommended)
- PCRE
- iconv
- gmp (this is a built-in extension as of PHP 7.2+)

example instalation:
``` bash
$ git pull https://github.com/bitclude/bitclude-php
$ cd bitclude-php
$ composer install
```

simple test:
``` php
include "ccxt.php";
var_dump (\ccxt\Exchange::$exchanges); // print a list of all available exchange classes
```

## Documentation
- [ccxt user manual](https://github.com/ccxt/ccxt/wiki)
- [bitclude api docs](https://docs.bitclude.com)
