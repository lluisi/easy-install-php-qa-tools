# Easy install PHP QA tools

Global installation of QA PHP tools like phpunit, phpmd, etc: 

* [phpunit] - PHPUnit is a programmer-oriented testing framework for PHP
* [phpmd] - PHP Mess Detector
* [phpcpd] - PHP Copy/Paste Detector
* [phing] - PHP project build system or build tool based on Apache Ant
* [phpcs] - PHP_CodeSniffer tokenizes PHP, JavaScript and CSS files and detects violations of a defined set of coding standards
* [phpdcd] - PHP Dead Code Detector

This bins are being moved to /usr/local/bin folder

### Usage

Clone it:
```
git clone https://github.com/lluisi/easy-install-php-qa-tools.git && cd easy-install-php-qa-tools
```

And then use it:
```sh
$ cd easy-install-php-qa-tools
$ ./easy
```

>You need composer installed globally. But don't worry the script will check this dependency and install globally on your computer if there isn't.


Note: also runs on OSX and Linux

[phpmd]:http://phpmd.org
[phpunit]:https://phpunit.de
[phpcpd]:https://github.com/sebastianbergmann/phpcpd
[phing]:http://www.phing.info
[phpcs]:https://github.com/squizlabs/PHP_CodeSniffer
[phpdcd]:https://github.com/sebastianbergmann/phpdcd
