# Easy install PHP QA tools

A really simple and easy script that downloads useful PHP QA tools like:

* [phpunit] - PHPUnit is a programmer-oriented testing framework for PHP
* [phpmd] - PHP Mess Detector
* [phpcpd] - PHP Copy/Paste Detector
* [phing] - PHP project build system or build tool based on Apache Ant

... and symlink the downloaded bins to your /usr/local/bin folder to be used globally.

### Installation

You need composer installed globally:

```sh
$ curl -sS https://getcomposer.org/installer | php
$ mv composer.phar /usr/local/bin/composer
```

Then, just clone this repository:
```sh
$ git clone https://github.com/lluisi/easy-install-php-qa-tools.git
$ cd easy-install-php-qa-tools
$ ./easy.sh
```

[phpmd]:http://phpmd.org
[phpunit]:https://phpunit.de
[phpcpd]:https://github.com/sebastianbergmann/phpcpd
[phing]:http://www.phing.info