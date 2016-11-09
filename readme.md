# SugaredRim\CS [![Code Climate](https://codeclimate.com/github/sugared-rim/cs/badges/gpa.svg)](https://codeclimate.com/github/sugared-rim/cs)

> Bunch of PHP codestyle linters sweetened with ease :cherries:

SugaredRim\CS takes an opinionated view of code style checking, it is preconfigured to get you up and running as quickly as possible.

## Install

```
$ composer require --dev sugared-rim/cs
```

## Usage

Just run `sugared-rim-cs` - that's it:

```json
{
    ...
    "require-dev": {
        "sugared-rim/cs": ...
    },
    "scripts": {
        "lint": "sugared-rim-cs"
    }
}
```

## Related

SugaredRim\CS uses the following packages:

* [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHPMD](https://github.com/phpmd/phpmd)
* [SugaredRim\PHP-CS-Fixer](https://github.com/sugared-rim/php-cs-fixer/)
* [SugaredRim\PHP_CodeSniffer](https://github.com/sugared-rim/php_codesniffer)
* [SugaredRim\PHPMD](https://github.com/schnittstabil/sugared-phpmd)

## License

MIT © [Michael Mayer](http://schnittstabil.de)
