# Joy NovaApi

This [Laravel](https://laravel.com/)/[Nova](https://nova.devdojo.com/) module adds REST Api with Passport and Swagger support to Nova.

By 🐼 [Ramakant Gangwar](https://github.com/rxcod9).

[![Screenshot](https://raw.githubusercontent.com/rxcod9/joy-nova-api/main/cover.jpg)](https://joy-nova.herokuapp.com/api/documentation)

[![Latest Version](https://img.shields.io/github/v/release/rxcod9/joy-nova-api?style=flat-square)](https://github.com/rxcod9/joy-nova-api/releases)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/rxcod9/joy-nova-api/run-tests?label=tests)
[![Total Downloads](https://img.shields.io/packagist/dt/joy/nova-api.svg?style=flat-square)](https://packagist.org/packages/joy/nova-api)

---

## Prerequisites

*   Composer Installed
*   [Install Laravel](https://laravel.com/docs/installation)
*   [Install Nova](https://github.com/the-control-group/nova)

---

## Installation

```bash
# 1. Require this Package in your fresh Laravel/Nova project
composer require joy/nova-api

# 2. Publish
php artisan vendor:publish --provider="Joy\NovaApi\NovaApiServiceProvider" --force

# 3. Generate Swagger Docs Json
php artisan joy-nova-api:l5-swagger:generate
```

---

<!-- ## Usage

Installation generates.

--- -->

<!-- ## Views Customization

In order to override views delivered by Nova DataTable, copy contents from ``vendor/joy/nova-api/resources/views`` to the ``views/vendor/joy-nova-api`` directory of your Laravel installation. -->

## Working Example

You can try laravel demo here [https://joy-nova.herokuapp.com/api/documentation](https://joy-nova.herokuapp.com/api/documentation).

## Documentation

Find yourself stuck using the package? Found a bug? Do you have general questions or suggestions for improving the joy nova-api? Feel free to [create an issue on GitHub](https://github.com/rxcod9/joy-nova-api/issues), we'll try to address it as soon as possible.

If you've found a bug regarding security please mail [gangwar.ramakant@gmail.com](mailto:gangwar.ramakant@gmail.com) instead of using the issue tracker.

## Testing

You can run the tests with:

```bash
vendor/bin/phpunit
```

## Upgrading

Please see [UPGRADING](UPGRADING.md) for details.

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email [gangwar.ramakant@gmail.com](mailto:gangwar.ramakant@gmail.com) instead of using the issue tracker.

## Credits

- [Ramakant Gangwar](https://github.com/rxcod9)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
