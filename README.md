# Easy install PHP QA tools

A really simple and easy script to allow PHP QA tools to be ready on your system.
This are the PHP QA tools:

* [phpunit] - PHPUnit is a programmer-oriented testing framework for PHP
* [phpmd] - PHP Mess Detector
* [phpcpd] - PHP Copy/Paste Detector
* [phing] - PHP project build system or build tool based on Apache Ant
* [phpcs] - PHP_CodeSniffer tokenizes PHP, JavaScript and CSS files and detects violations of a defined set of coding standards
* [phpdcd] - PHP Dead Code Detector

... and symlink the downloaded bins to your /usr/local/bin folder to be used globally.

### Usage

Clone this repository:
```sh
$ git clone https://github.com/lluisi/easy-install-php-qa-tools.git
```

And then use it:
```sh
$ cd easy-install-php-qa-tools
$ ./easy
```

>You need composer installed globally. Will check this dependency for you and ask to install if there isn't available.


Note: also runs on OSX and Linux

[phpmd]:http://phpmd.org
[phpunit]:https://phpunit.de
[phpcpd]:https://github.com/sebastianbergmann/phpcpd
[phing]:http://www.phing.info
[phpcs]:https://github.com/squizlabs/PHP_CodeSniffer
[phpdcd]:https://github.com/sebastianbergmann/phpdcd