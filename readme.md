# Sugared\CS [![Code Climate](https://codeclimate.com/github/schnittstabil/sugared-cs/badges/gpa.svg)](https://codeclimate.com/github/schnittstabil/sugared-cs)

> Bunch of PHP codestyle linters sweetened with ease :cherries:

Sugared\CS takes an opinionated view of code style checking, it is preconfigured to get you up and running as quickly as possible.

## Install

```
$ composer require --dev schnittstabil/sugared-cs
```

## Usage

Just run `sugared-cs` - that's it:

```json
{
    ...
    "require-dev": {
        "schnittstabil/sugared-cs": ...
    },
    "scripts": {
        "lint": "sugared-cs"
    }
}
```

## Related

Sugared\CS uses the following packages:

* [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHPMD](https://github.com/phpmd/phpmd)
* [Sugared\PHP-CS-Fixer](https://github.com/schnittstabil/sugared-php-cs-fixer/)
* [Sugared\PHP_CodeSniffer](https://github.com/schnittstabil/sugared-php_codesniffer)
* [Sugared\PHPMD](https://github.com/schnittstabil/sugared-phpmd)

## License

MIT © [Michael Mayer](http://schnittstabil.de)
