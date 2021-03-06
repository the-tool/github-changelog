# CONTRIBUTING

## Coding Standards

This project has subscribed to [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
and uses [`fabpot/php-cs-fixer`](https://github.com/FriendsOfPHP/PHP-CS-Fixer) to enforce coding standards.

Run

```
$ make cs
```

to ensure your changes to not break the build.

## Tests

This project uses [`phpunit/phpunit`](https://github.com/sebastianbergmann/phpunit) to drive the development using tests.

Run

```
$ make test
```

to run the tests.
