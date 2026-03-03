# Reply To Verify

[![Latest Version on Packagist](https://img.shields.io/packagist/v/maaz-azeemi/reply-to-verify.svg?style=flat-square)](https://packagist.org/packages/maaz-azeemi/reply-to-verify)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/Maaz0313-png/reply-to-verify-email/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/Maaz0313-png/reply-to-verify-email/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/Maaz0313-png/reply-to-verify-email/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/Maaz0313-png/reply-to-verify-email/actions?query=workflow%3A"Fix+PHP+code+style+issues"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/maaz-azeemi/reply-to-verify.svg?style=flat-square)](https://packagist.org/packages/maaz-azeemi/reply-to-verify)

A Laravel package that lets users verify their email address simply by replying to a verification email containing a one-time code.

## Requirements

- PHP ^8.3
- Laravel 11.x, 12.x, or 13.x

## Installation

You can install the package via composer:

```bash
composer require maaz-azeemi/reply-to-verify
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="skeleton-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="skeleton-config"
```

This is the contents of the published config file:

```php
// config for MaazAzeemi/ReplyToVerify
return [

];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="skeleton-views"
```

## Usage

```php
use MaazAzeemi\ReplyToVerify\Skeleton;

$replyToVerify = new Skeleton();
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Maaz Azeemi](https://github.com/Maaz0313-png)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
