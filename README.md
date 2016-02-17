phpqrcode
=========
phpqrcode

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist hoter/phpqrcode "dev-master"
```

or add

```
"hoter/phpqrcode": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \hoter\phpqrcode\AutoloadExample::widget(); ?>```