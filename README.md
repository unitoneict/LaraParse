# LaraParse

Before even Parse take a desision to close the cloud host in 2017, we at Unit One start developing our own parse server implemtnation as a Laravel package.

You can install the package via composer

```
composer require unitoneict/lara-parse
```

Then you need to add `LaraParseServiceProvider` to your `config/app.php` provider

```php
  'providers' => [
        /*
         * Application Service Providers...
         */
        ...
        UnitOneICT\LaraParse\LaraParseServiceProvider::class
    ],
```
