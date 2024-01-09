FirebirdSQL Extension for Yii 2 and PHP 8.3
==========================
[![Latest Stable Version](https://poser.pugx.org/marcinmisiak/yii2-firebird/v/stable)](https://packagist.org/packages/marcinmisiak/yii2-firebird)
[![Total Downloads](https://poser.pugx.org/marcinmisiak/yii2-firebird/downloads)](https://packagist.org/packages/marcinmisiak/yii2-firebird)
[![Latest Unstable Version](https://poser.pugx.org/marcinmisiak/yii2-firebird/v/unstable)](https://packagist.org/packages/marcinmisiak/yii2-firebird)
[![License](https://poser.pugx.org/marcinmisiak/yii2-firebird/license)](https://packagist.org/packages/marcinmisiak/yii2-firebird)


Forked
-----------

Forked from edgardmessias/yii2-firebird
```html
[edgardmessias/yii2-firebird](https://github.com/edgardmessias/yii2-firebird).
```

Requirements
------------

At least Firebird version 2.0 is required. However, in order to use all extension features.

Partial support with Firebird 3.0

PHP 8.3

Installation
------------

The preferred way to install this extension is through [composer](https://getcomposer.org/download/).

Either run

```bash
php composer.phar require --prefer-dist marcinmisiak/yii2-firebird "*"
```

or add 

```json
"marcinmisiak/yii2-firebird": "*"
```

to the require section of your `composer.json` file.


Configuration
-------------

To use this extension, simply add the following code in your application configuration:

```php
return [
    //....
    'components' => [
        'db' => [
            'class' => 'marcinmisiak\db\firebird\Connection',
            'dsn' => 'firebird:dbname=localhost:/tmp/TEST.FDB;charset=UTF8',
            'username' => 'username',
            'password' => 'password',
            'enableSchemaCache' => true,
            'schemaCacheDuration' => 43200,
            'schemaCache' => 'cache',
            'emulatePrepare' => true,
            'attributes' => [
                PDO::ATTR_PERSISTENT => true
            ],
        ],
    ],
];
```

## Donations:
* Donation is as per your goodwill to support my development.
* If you are interested in my future developments, i would really appreciate a small donation to support this project.
```html
My FWH wallet
0x70368081c706178dbda7aa444f99ad675a82c24c
https://freewallet.org/id/8c09767c/eth
```
```html
My Bitcoin Wallet Address (BTC)
bc1qv8e7qztkd5cekzz89nlfxed9clfhpv8t2jn9rf
https://freewallet.org/id/8c09767c/btc
```
```html
My Ethereum Wallet Address (ETH)
0x70368081c706178dbda7aa444f99ad675a82c24c
https://freewallet.org/id/8c09767c/eth
```
Another Cryptocurrency: https://freewallet.org/id/8c09767c






