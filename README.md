

# integrate laravel app with odoo

---
This repo can be used to scaffold a Laravel package. Follow these steps to get started:

1. Press the "Use template" button at the top of this repo to create a new repo with the contents of this skeleton.
2. Run "php ./configure.php" to run a script that will replace all placeholders throughout all the files.
3. Have fun creating your package.
4. If you need help creating a package, consider picking up our <a href="https://laravelpackage.training">Laravel Package Training</a> video course.
---
<!--/delete-->
## Installation

You can install the package via composer:

```bash
composer require aabadawy/laravel-odoo-integration
```

You can publish the config file with:

```bash
php artisan vendor:publish --provider="Aabadawy\LaravelOdooIntegration\LaravelOdooIntegrationServiceProvider" --tag="config"
```

This is the contents of the published config file:

```php
return [
    'default'   => [
        'token' => env('ODOO_TOKEN'),
        'url' => env('ODOO_URL'),
        'user_id' => '1',
    ]
];
```


## Usage

```php

```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](https://github.com/spatie/aabadawy/blob/main/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
