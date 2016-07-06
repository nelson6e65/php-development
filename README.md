# php-development
Global packages and CLI tools to be used in PHP development.

## CLI Tools
- [PHPUnit](https://phpunit.de/) (**`phpunit`**): The PHP Testing Framework.
- [ApiGen](http://www.apigen.org/) (**`apigen`**): Smart and Readable Documentation for your PHP project.
- [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) (**`phpcs`**, **`phpcbf`**): Tokenizes PHP, JavaScript and CSS files and detects violations of a defined set of coding standards.

### Installing

> Note: The following instructions asumes that you have [`composer` installed globally](https://getcomposer.org/doc/00-intro.md#globally).

#### Global
This installs CLI tools in global PATH to be used directly:

```sh
composer global require nelson6e65/php-development
```

- `phpunit --version`
- `apigen --version`
- `phpcs --version`
- `phpcbf --version`


#### As development requirement
This installs CLI tools as dev requirements to be distributed with your package (see `composer install`):

```sh
composer require --dev nelson6e65/php-development
```

- `vendor/bin/phpunit --version`
- `vendor/bin/apigen --version`
- `vendor/bin/phpcs --version`
- `vendor/bin/phpcbf --version`
