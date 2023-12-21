FirebirdSQL
===========
Firebird 3 + php8.1

Installation
------------

The preferred way to install this extension is through [composer](https://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist marcinmisiak/yii2-firebird "*"
```

or add 

```
"marcinmisiak/yii2-firebird": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \marcinmisiak\db\firebird\AutoloadExample::widget(); ?>```
